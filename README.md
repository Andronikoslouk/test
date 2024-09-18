# test
# hello world

 add_row
 # Good
add_row()
permute()

# Bad
row_adder()
permutation()
# Good

# Objects like data frames are treated as leaves
x <- map_if(x, is_bare_list, recurse)


# Bad

# Recurse only with bare lists
x <- map_if(x, is_bare_list, recurse)
