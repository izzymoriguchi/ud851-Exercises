# Toy App Exercise Repo

This is a exercise repository for Developing Android Apps.

## ud851-Exercises
  - Lesson01-Favorite-Toys
  - [Lesson02-GitHub-Repo-Search](#Lesson02-GitHub-Repo-Search)
  - [Lesson03-Green-Recycler-View](#Lesson03-Green-Recycler-View)
  - [Lesson04a-Starting-New-Activities](#Lesson04a-Starting-New-Activities)
  - [Lesson04b-Webpages-Maps-and-Sharing](#Lesson04b-Webpages-Maps-and-Sharing)
  - [Lesson05a-Android-Lifecycle](#Lesson05a-Android-Lifecycle)
  - [Lesson05b-Smarter-GitHub-Repo-Search](#Lesson05b-Smarter-GitHub-Repo-Search)
  - [Lesson06-Visualizer-Preferences](#Lesson06-Visualizer-Preferences)
  - [Lesson08-Quiz-Example (Content Providers)](#Lesson08-Quiz-Example (Content Providers))
  - [Lesson09b-ToDo-List-AAC (Android Architecture Components)](#Lesson09b-ToDo-List-AAC (Android Architecture Components))

### Lesson02-GitHub-Repo-Search
- T02.01-Exercise-CreateLayout
- T02.02-Exercise-AddMenu
  - Learn how to create a menu
  - Add the menu item for search to the Menu Resource, setting it to showAction ifRoom
  - Inflate the menu using onCreateOptionsMenu
  - Display a toast using onOptionsItemSelected when Search is selected
- T02.03-Exercise-DisplayUrl
  - Build the Url that will be used to query Github and display it when the Search button is pressed
- T02.04-Exercise-ConnectingToTheInternet
  - Add internet permision.
- T02.05-Exercise-CreateAsyncTask
- T02.06-Exercise-AddPolish

### Lesson03-Green-Recycler-View
- T03.01-Exercise-RecyclerViewLayout
  - Create a layout for a RecyclerView
  - Add a required dependency in Gradle for using RecyclerView
- T03.02-Exercise-ViewHolder
  - Adding Items to RecyclerView
    - Create a layout file for RecyclerView list item
    - Add ViewHolder to adapter to cache the view holders
- T03.03-Exercise-RecyclerViewAdapter
  - Learn how to create Adapter
  - Learn how to override three functions for Adapter
- T03.04-Exercise-WiringUpRecyclerView
  - Learn how to connect all the components for RecyclerView
    - How to use LayoutManager
    - Define RecyclerView, Adapter and LayoutManager
    - Connect everything together
- T03.07-Exercise-RecyclerViewClickHandling
  - Learn how to do click handling of list items
    - Create an your own interface ItemClickListener within Adapter
    - In the inner ViewHolder class, implement library View.OnClickListener and trigger to call your own listener method on "onClick" method

### Lesson04a-Starting-New-Activities
  - T04a.01-Exercise-AddNewActivity
    - Learn how to create a new activity 
    - Learn how to have a "Go back" button on child activity
      - Add <meta-data> tag on Manifest
  - T04a.02-Exercise-StartNewActivity
    - Learn how to start a new activity
  - T04a.03-Exercise-PassingDataBetweenActivities
    - Learn how to send and receive data through intent

### Lesson04b-Webpages-Maps-and-Sharing
  - Learn about implicit intent
    - T04b.01-Exercise-OpenWebpage
      - Learn about how to use implicit intent to open a web page from an app
    - T04b.02-Exercise-OpenMap
      - Learn how to use implicit intent to open specific location on a map
      - Learn how to create Uri from String using Uri.Builder
    - T04b.03-Exercise-ShareText
      - Learn how to share contents to other apps using ShareCompat
      - Learn how to use ShareCompat.IntentBuilder

### Lesson05a-Android-Lifecycle
  - T05a.01-Exercise-LogLifecycle
    - Learn about the basic flow of Android life cycle
    - onCreate, onStart, onResume, onPause, onStop, onDestroy
  - T05a.02-Exercise-PersistData
    - Learn how to use onSaveInstanceState with Bundle
    - check Bundle in onCreate to see if we saved any instance
  - T05a.03-Exercise-FixLifecycleDisplayBug
    - Learn how to show onPause and onDestroy on textview using ArrayList
    - Learn when we get onRestart

### Lesson05b-Smarter-GitHub-Repo-Search
  - T05b.01-Exercise-SaveResults
    - Using Github repo search example, learn how to preserve data when screen rotation happens
      - Save TextView data in onSaveInstanceState through Bundle
      - Get the saved data in onCreate when Bundle object savedInstanceState is not null
  - T05b.02-Exercise-AddAsyncTaskLoader
    - Learn how to use AsyncTaskLoader to deal with issues when device rotation during thread execution happens
  - T05b.03-Exercise-PolishAsyncTask
    - Learn about caching in AsyncTaskLoader
      - Store some variables for cached results
      - Use(override) deliverResult in the case of caching

### Lesson06-Visualizer-Preferences
  - T06.01-Exercise-SetupTheActivity
    - Using Visualizer app, learn how to set up preferences
      - Create settings menu that opens up new activity
  - T06.02-Exercise-MakeAPreferenceFragment
    - Create PreferenceFragment 
      - Add a PreferenceFragment class that extends PreferenceFragmentCompat
      - Create a layout file for the fragment
      - Add the fragment by putting the fragment tag in the Activity layout file
      - Add the theme for the preference (required)
  - T06.03-Exercise-ReadingFromSharedPreferences
    - Read preferences from SharedPreferences and update
      - Get default shared preference by calling getDefaultSharedPreferences
  - T06.04-Exercise-UseResources
    - Learn how to use strings and bools resources for string/boolean constants 
  - T06.05-Exercise-PreferenceChangeListener
    - PreferenceChangeListener allows the preference change to be updated right away
    - Learn how to add PreferenceChangeListener
  - T06.06-Exercise-AddTwoMoreCheckboxes
    - Create 2 more checkboxes for treble and mid-range
  - T06.07-Exercise-ListPreference
    - Learn how to create ListPreference
  - T06.08-Exercise-PreferenceSummary
    - Learn about PreferenceSummary (the current status of each user's preference item)
      - Add preference summary for ListPreference
  - T06.09-Exercise-EditTextPreference
    - Learn how to add EditTextPreference
  - T06.10-Exercise-EditTextPreferenceConstraints
    - Use OnPreferenceChangeListener in addition to OnSharedPreferenceChangeListener to handle the input error
    - Difference
      - SharedPreferenceChangeListener is triggered after any value is saved to the SharedPreferences file.
      - PreferenceChangeListener is triggered before a value is saved to the SharedPreferences file. Because of this, it can prevent an invalid update to a preference.  

### Lesson08-Quiz-Example (Content Providers)
  - T08.01-Exercise-AddTheContentProviderPermission
    - Add permission for read operation on manifest
  - T08.02-Exercise-AddAsyncTaskToRetrieveCursor
    - Practice using ContentResolver to query and get Cursor object through AsyncTask
  - T08.03-Exercise-FinishQuizExample
    - Retrieve Cursor object on AsyncTask, and get data from Cursor object 

### Lesson09b-ToDo-List-AAC (Android Architecture Components)
  - T09b.01-Exercise-CreateEntity
    - Use Room
      - Add dependency for Room
      - Use annotations for Room (@Entity, @PrimaryKey, @Ignore)
  - T09b.02-Exercise-SaveTaskInDatabaseFromAddTaskActivity
    - Learn how to create AppDatabase, and how to add TaskEntry
    - DateConverter, TaskDao idea used
  - T09b.03-Exercise-RetrieveTasksFromDatabaseAtMainActivity
    - Add AppDatabase in MainActivity and let the adapter load TaskEntry lists through TaskDuo every time onRestore() method is called. 



