if(PPLNN_USE_X86)
    file(GLOB PPLNN_SAMPLES_API_SRC *.cc)
    add_executable(pplnn_samples_api_intro ${PPLNN_SAMPLES_API_SRC})
    target_link_libraries(pplnn_samples_api_intro PUBLIC pplnn_static)
endif()
