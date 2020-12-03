# async_list_view

A wrapper around `StreamSummaryBuilder` and `ListView` that displays a
scrollable list of items lazily fetched from an asynchronous data source.
AsyncListView is useful for loading a list of results from an asynchronous
database. Example use cases:
 * display user chat history retrieved from Firestore.
 * display search results for items on an online marketplace.
 
`T` is the event type of the provided source stream.

*Disclaimer:* I have no idea what I'm doing and this package isn't unit tested.
Use at your own risk. Any contributions to this package are highly welcome.
