add_llvm_library(LLVMCheerpUtils
  AllocaMerging.cpp
  AllocaLowering.cpp
  GlobalDepsAnalyzer.cpp
  IdenticalCodeFolding.cpp
  NativeRewriter.cpp
  PreExecute.cpp
  PointerAnalyzer.cpp
  PointerPasses.cpp
  GEPOptimizer.cpp
  CFGPasses.cpp
  ReplaceNopCastsAndByteSwaps.cpp
  Registerize.cpp
  StructMemFuncLowering.cpp
  TypeOptimizer.cpp
  Utility.cpp
  ExpandStructRegs.cpp
  FixIrreducibleControlFlow.cpp
  )

add_dependencies(LLVMCheerpUtils intrinsics_gen)
