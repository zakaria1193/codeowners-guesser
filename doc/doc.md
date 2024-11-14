# Public API

// main.cpp
gen_codeowners_file(GeneratorCfg&);

// lower level API
find_code_owner_for_file(std::pathname); // With whole file as context
find_code_owner_for_line_range(std::pathname, int line);







# Internal implem

Main goal:

input: git repo
output: CODEOWNERS file

# 
