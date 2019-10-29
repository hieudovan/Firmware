px4_add_module(
    MODULE aplication
    MAIN simple_app
    STACK_MAIN 2000
    SRCS
        simple_app.c
    DEPENDS
    )