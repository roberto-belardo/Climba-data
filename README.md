![Climba Logo](http://i.imgur.com/m8RZceD.png)

Climba-data
===========

A community driven open source json database of italian climbing spots with sector, routes and infos. 

## Table of contents
- [What is Climba-data](#what-is-climba-data)
- [What you can do with Climba-data](#what-you-can-do-with-climba-data)
 - [Project Structure](#project-structure)
 - [Improvements](#improvements)
- [Contributors](#contributors)
- [Credits](#links)
- [Copyright](#copyright)
- [License](#license)

## What is Climba-data
Climba-data is a community driven open source json database of italian climbing spots. The list of all available climbing spots is on this project's [Wiki](https://github.com/backslash451/Climba-data/wiki/).

## What you can do with Climba-data
You can:
- download it and build whatever you like. We used it to build [Climba](https://github.com/backslash451/Climba), an iOS app.
- suggest a revision
- add a new climbing spot

### Project Structure
Climba-data is structured as a list of json files, one for each italian region. To add a new region file please just copy the syntax used in Lazio.json.

Every climbing spot should have at least the following informations:
 - Name
 - Latitude
 - Longitude
 - Access infos
 - Description
 - Province
 - Province code
 - List of sectors
  - sector name
  - list of routes
    - route name
    - route grade

### Improvements
Here is a short list of suggested improvements that could be added to every crag, sector, route:

#### Crag
##### History
> (String) Short notes about the history of the crag, when it was born, by who etc...

Example:
```json
"history": "This crag was born in 1922..."
```

##### Rock Type
> (String) Rock typology

Example:
```json
"rock_type": "limestone"
```

##### Authors
> (List) Name and surname of who built the crag

Example:
```json
"authors": [
 {name: "Mario", surname: "Rossi", nickname:"red"},
 {name: "Carlo", surname: "Bianchi", nickname:"white"}
]
```

##### Notes
> (String) Special noteson the crag

Example
Example:
```json
"notes": "Pay attention to the birds during the winter because ..."
```

#### Sector
##### History
> (String) Short notes about the history of the sector, when it was born, by who etc...

Example:
```json
"history": "This crag was born in 1922..."
```

##### Authors
> (List) Name and surname of who built the sector

Example:
```json
"authors": [
 {name: "Mario", surname: "Rossi", nickname:"red"},
 {name: "Carlo", surname: "Bianchi", nickname:"white"}
]
```

##### Notes
> (String) Special noteson the crag

Example
Example:
```json
"notes": "Pay attention to the birds during the winter because ..."
```

#### Route
##### Authors
> (List) Name and surname of who built the route

Example:
```json
"authors": [
 {name: "Mario", surname: "Rossi", nickname:"red"},
 {name: "Carlo", surname: "Bianchi", nickname:"white"}
]
```

##### Length
> (Number) Length of the route expressed in meters.

Example:
```json
"length": "22"
```

##### Notes
> (String) Special noteson the route

Example
Example:
```json
"notes": "Pay attention to the last spit because is very old..."
```

## Contributors
<a href="https://twitter.com/robertobelardo" target="_blank"><img src="https://avatars3.githubusercontent.com/u/43101?v=2&s=96" alt="Roberto Belardo"></a>  
**Roberto Belardo** — Author 
<a href="https://twitter.com/robertobelardo" target="_blank">@robertobelardo</a>

## Links
 - [Climba on GitHub](https://github.com/backslash451/Climba)
 - [Climba on AppStore]()
 - [Website](http://climba.parseapp.com)
 - [Facebook](https://www.facebook.com/climba.app.page)
 - [Twitter](https://twitter.com/climba_app)
 - [Blog](http://backslash451.github.io)

## Copyright
Climba-data is a free, open source, community driven project. This doesn't mean you can steal other's material and copy it here. So please, please, please, do not steal other's people job.

## License
This work is licensed under a **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License**. 

![Creative Commons License Logo](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png "License")
