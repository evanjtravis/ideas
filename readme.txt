    Ultimately, defining the effects of any given mechanic on external attributes (of the game world or player) allows the developer to see which variables and settings are important in a given game context and to abstract out mechanic-to-state interactions in favor of mechanic-to-mechanic interactions.


TODO List:
# General #
[ ] Create meta.config files for all project directories.
[ ] Short script to create new meta file in a directory.
    [ ] Does not overwrite old meta files
[ ] Script to merge two config files into one new file
    [ ] Does not consume old files
    [ ] Appends value from one section/variable to another with an new line, easily readable delimiter, and another new line.
    [ ] Similarly named sections are grouped together

# MDA #
[ ] Define/ enumerate state variables
    - In the future, undefined state variables could either be defined as their own, discrete, self-contained variables, or, defined as COMPOUND VARIABLES, that might not necessarily need literal definintion, but rather can be drived based off of current and a change in previous state attribute values.
[ ] Define scheme to compress data that tracks state changes to increasingly generalize results that occurred in the past. Keeping multiple copies of a state would be very difficult and consume much too much memory.
