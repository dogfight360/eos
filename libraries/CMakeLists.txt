add_subdirectory( fc )
add_subdirectory( builtins )
add_subdirectory( softfloat )
add_subdirectory( chainbase )
add_subdirectory( wasm-jit )
add_subdirectory( utilities )
add_subdirectory( appbase )
add_subdirectory( chain )
add_subdirectory( testing )
add_subdirectory( abi_generator )

install(DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}/chainbase/include/chainbase DESTINATION ${CMAKE_INSTALL_FULL_INCLUDEDIR})
install(DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}/softfloat/source/include DESTINATION ${CMAKE_INSTALL_FULL_INCLUDEDIR}/eosio/softfloat)
