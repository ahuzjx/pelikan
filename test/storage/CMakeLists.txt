add_subdirectory(cuckoo)
add_subdirectory(slab)
if(USE_PMEM)
    add_subdirectory(cuckoo_pmem)
    add_subdirectory(slab_pmem)
endif(USE_PMEM)
