cmake_minimum_required(VERSION 3.4.1)


include_directories(
        fb
        Foundation
        HookZz
        Jni
        Substrate
)

add_library(
        Jni/VAJni.cpp
        Foundation/IOUniformer.cpp
        Foundation/VMPatch.cpp
        Foundation/SymbolFinder.cpp
        Foundation/Path.cpp
        Foundation/SandboxFs.cpp
        Substrate/hde64.c
        Substrate/SubstrateDebug.cpp
        Substrate/SubstrateHook.cpp
        Substrate/SubstratePosixMemory.cpp
)