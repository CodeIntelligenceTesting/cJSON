#cifuzz:build-template:begin
#add_fuzz_test({{ .FuzzTestName }} {{ .FileName }})
#target_include_directories({{ .FuzzTestName }} PRIVATE ${PROJECT_SOURCE_DIR})
#target_link_libraries({{ .FuzzTestName }} PRIVATE ${CJSON_LIB})
#cifuzz:build-template:end
