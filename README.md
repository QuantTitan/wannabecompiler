# toy_compiler_for_fun

## llvm 15 compatibility

## run 
./parser example.txt

## debug

lldb ./parser
breakpoint set --file codegen.cpp --line 80
run example.txt
