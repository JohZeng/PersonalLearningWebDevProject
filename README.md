# PersonalLearningWebDevProject

# Notes and Tips:

# index.html is usually the initial file
# Use developer tool to review the backend of html web code

# When using CSS, there are multiple ways to style html 
# 1. Inline CSS - where you add the formatting in the html file itself. Downside is that this si very messy/clutters code and inefficient to udpate
# 2. Internal Style Sheet - Where in the header of the html file, you can define the style sheet. Can clutter up code still
# 3. External CSS - Creating a external CSS file that will keep all the styling. (Recommended)

# Inspector/Developer tool can be used to review and see the backend of any html pages. This can also be used to see how it is seen in different browsers and mobile view.

# Combinators - Combines multiple selections of elements.
# 1. Descendent Selectors - Selects all the elements that are a child of the parent element regardless of how deep the nesting goes.
# 2. Child Selectors - Selects all only the elements that are that are a direct descendent of parent element. Only goes one level deep.

# Grouping - Helps removed redundancy in css code. Used when there are multiple types of elements that have the same type of formatting. Represented by comma ','
#   - Can also be used to group class and ids

# Specificty - Takes and adds a weight value to a selector (element/class/id selectors). THen it adds a point value to it to determine what style rules to be applied. Most Specificity values takes precedence and goes first. If Specificity is the same, then apply the latest styling rule.
# [Style Attribute],[ID],[Class, Pseudo-Class, Attribute],[Elements]
# Most Specificity Value  <----------------> Least Specificity Value