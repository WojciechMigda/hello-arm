add_executable( hello-arm "src/dummy.cpp" )
target_sources( hello-arm PRIVATE "src/main.cpp" )

#target_link_libraries( FreeCalculator
#    PRIVATE MyCalc::basicmath
#            Boost::program_options )

