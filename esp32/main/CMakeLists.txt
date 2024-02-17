idf_component_register(SRCS "app_main.c"
                    "../../core_list_join.c"
                    "../../core_main.c"
                    "../../core_matrix.c"
                    "../../core_state.c"
                    "../../core_util.c"
                    "posix/core_portme.c"

                    INCLUDE_DIRS "" "../.." "posix")

target_compile_options(${COMPONENT_LIB} PRIVATE "-O3")
