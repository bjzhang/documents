
Summary the way that how does cpu work with a device in Linux kernel?
=

Using a device without coherent support
-

Using a device with coherent support
-

1.  SMMU

2.  iova
    iova came from pci subsystem used by intel. It is moved to iommu subsystem in 2011.
    Recently, ARM is working on enable iova in arm smmu.
    if iova is enabled, smmu init code will register a dma_ops in order to replace the original dma ops(swiotlb and cma).

-

Other
-

uio

