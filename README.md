# plugin-integration-testing
Build definitions for integration testing Please plugins

# plz_e2e_test
A light weight test that runs Please in the current repo. It has a number of arguments that you can use to test various 
conditions around the output of the command. 

# please_repo_e2e_test
Similar to `plz_e2e_test` however it runs Please in the test repo passed in via the `repo` argument. Use `BUILD_FILE` 
instead of `BUILD` as the build file name in the test repo to avoid collisions with the main Please repo. 