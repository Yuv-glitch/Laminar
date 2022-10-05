# Laminar

ML model version management tool:robot:
![bg3](https://user-images.githubusercontent.com/68955738/194013559-88c6f3d2-3cbf-4e56-9abd-15ebfb500d69.png)



# About 
Making ML models and maintaining their versions can get messy quick especially when there are hundreds of versions and their properties to manage, laminar solves the problem of storing all these hyperparameteres/metadata to help you keep notes of your models :face_exhaling:

# Getting started
Download the files 
``` 
laminar.exe
settings.json
store.db

``` 
>Always remember to store all three of the files in the same directory

And thats it you do not need to install anything just plug and play:sunglasses:

# Commands

## The create command ##
The create command creates a directory at the location of your choice (if no path is selected) a window will open to select the directory where you want to store the files

After selecting your directory you can type   **create [name]**

For example

``` create test ```

>Something to remember here is that once you select a directory all the future models(model here is referred to the json file storing the metadata you just entered) would be stored at that path, to change the path you can use the ``` setpath ``` command:heart:

## Adding versions ##
To add versions to your models you can simply type **add version to [name]**

```add version to test```

>Version can be added to only the model created with laminar and if the files or the path it was stored in are not changed :heart:

## Deleting a model
To delete a model and its versions you can type **delete model [name]**

``` delte model test ```

>Model can be only be deleted if it was created with laminar and if the files or the path it was stored in are not changed :heart:

## Deleting all versions 
To delete all the versions excepet the main model you can type in **delete all versions [name]** 

```delete all versions test```

>Versions can only be deleted if they were created with laminar and if the files or the path it was stored in are not changed :heart: 

## Deleting a specific version 
To delete a specific version you can type **delete version**

```delete version```

>Version can only be deleted if they were created with laminar and if the files or the path it was stored in are not changed :heart:

##Listing out the current models made
To list all the models present currently you can type **listmodels**

```listmodels```

>Models made with laminar along with their respective path would be listed :heart:

## Viewing a specific object of a model 
To view a specific object for example the name or the version you can type **list**

```list```

The available objects to list are 
- name
- model-version
- model-type
- hyperparameters
- performance-scores
- database-type
- note

# Some wranings :point_down:
- Its always a good idea to make a new empty directory to store all the models 
- Two hyperparameters or Performance scores cannot be the same name
- When deleting always make sure important files with the same name do not exist in the model directory to avoid deleting of important files
- Avoid same naming two undeleted models and versions  
- Make sure to always delete a model created with laminar to delete it with laminar 
- Keep the settings.json, store.db and laminar.exe in the same directory 


# Note
Please remember that laminar is currently in its baby(beta) stages and may often be buggy or cause problems

# Contact :see_no_evil:

You can contact me on discord *dumb_potato#1734*

# Finishing 

Made with :heart: and python


