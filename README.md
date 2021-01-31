# Windows-Update-for-multiple-offline-environments

This set of scripts and task provides an offline update process that will allow a single WSUS server to be utilized for multiple offline environments. This is possible because the WSUS server does not have any computer entries and only handles organizing the hierarchy of updates to be downloaded. The turnaround time to complete multiple update cycles is faster because you do not need to export/import the WSUS database or have a 1:1 relation of WSUS servers to offline environments. Just the updates that are needed are brought into the offline environment.  Client managment scripts are also included to automate deployment of the updates once in the environment.



This is a reposting from my Microsoft Technet Gallery.
