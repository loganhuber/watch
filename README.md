# Watch

##### Simple shell tool for quickly traversing deep directories. Add this to your ~/bin and you'll be whipping around the filesystem like Dale Earnhardt

### Example use:

*store path string*
    
    cd /Users/your_name/Documents/reaper_projects/projects/smoke_on_the_water

    watch

*print list of saved paths*

    watch -p

    output: 1) /Users/your_name/Documents/reaper_projects/projects/smoke_on_the_water




*copy path to clipboard wrapped in double quotes*

    cd ~
    watch -cp 1
    cd *command v to paste*

Path strings are saved in a .txt file and will exist between terminal sessions. 

To clear the paths run:

    watch -clr

    watch -p
    output: none



