# Distributed Product Lifecycle Management
Currently PLM systems, such as Teamcenter by Siemans and ARAS, consist of a centralized database backend and client applicatons to access the data. These systems require alot of knowledge to setup and manage. Also, there overall cost can be prohibative to smaller companies. I'm proposing a git style system. This would requires some individual that manages a master copy of the repository. Other stake holders can clone the repo for referance or to create a branch to propose changes. This doesn't exclude a central data store like github but doesn't require one either.

## Initial thoughts

Git repositoties contain many files. But individuale files don't require there own trackable history. In a system designed for mechanical parts a repo may contain many end items whose individual versions need to be tracked. A branch would referance particular versions of these items.
