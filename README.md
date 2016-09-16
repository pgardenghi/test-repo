Hello Cloud guru Users, You are the best!

This is my test Changes
# test-repo

# Interesting Markup
cellForRowAtIndexPath gets called for every cell (also during scrolling). If you are trying to do too much, it won't scroll smooth. Furthermore cells are reused (as dequeue indicates it). iOS only creates the number of visible cells instances plus one or two extra cells. If a cell is reused, you would need to remove the already added labels before adding new ones which leads to the next problem: How can you identify them (either search for all subviews and check if it is an instance of UILabel or use a tag and find them by tag.... anyway: If you are trying to do too much, it won't scroll smooth.
