# Toy App Exercise Repo

This is a exercise repository for Developing Android Apps.

## ud851-Exercises
  - Lesson01-Favorite-Toys
  - Lesson02-GitHub-Repo-Search
  - [Lesson03-Green-Recycler-View](#Lesson03-Green-Recycler-View)
  - [Lesson04a-Starting-New-Activities](#Lesson04a-Starting-New-Activities)
  - [Lesson04b-Webpages-Maps-and-Sharing](#Lesson04b-Webpages-Maps-and-Sharing)

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


