## Multi-Context CoreData

Using CoreData in conjunction with NSFetchedResultsController greatly simplifies dealing with any sort of list of items which you would display in a table view.

There are two scenarios where you would want to branch out, that is, use multiple managed object contexts: 1) to simplify adding/editing new items and 2) to avoid blocking the UI. In this post I want to review the ways to set up your contexts to get you what you want.

Note: I am wrapping my head around this myself for the very first time. Please notify me via e-mail about errors that I might have made or where I am explaining something incorrectly.
