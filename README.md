# UITableView

```
numberOfRowsInSelection
cellForRowAt
didSelectRowAt
deselectRow
dequeueReusableCell
cellForRow
```

# Reload TableView Data
                  
```
self.tableView.reloadData()

App Launched -> App Visible -> App Receeds Into Background -> Resources Reclaimed
```

# Various Ways Of Storing Data

```
UserDefaults -> small piece of data
Codable -> plist
KeyChain -> passwords
SQLite -> large amount of data
CoreData -> object oriented database
Realm -> faster and easier to use
```

# CoreData Terminology
```
Entity -> Class -> Taale

Property -> Attribute -> Field
```

# Guard

```
It is defined as a stmt that is used to transfer progrom control out of the scope if condition aren't met
```

# Colors

```
Chamelon
```

# Execute code under main thread from separate thread

```
func searchBar(_ searchBar:UISearchBar,textDidChange searchText:String){
  DispatchQueue.main.async{
    searchBar.reassignFirstResponder()
  }
}
```

# Packages

```
PropertyListEncoder
PropertyListDecoder
UserDefaults.standard
NSSearchPathForDirectoriesInDomain
NSPersistentContainer
NSFetchRequest
NSPredicate
Item()
```
