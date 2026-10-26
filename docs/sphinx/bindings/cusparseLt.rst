.. module:: nvmath.bindings.cusparseLt

cuSPARSELt (:mod:`nvmath.bindings.cusparseLt`)
==============================================

For detailed documentation on the original C APIs, refer to the `cuSPARSELt documentation
<https://docs.nvidia.com/cuda/cusparselt/>`_.

These bindings cover cuSPARSELt versions 0.7.1 through 0.10.0. The public C APIs
and enums in cuSPARSELt 0.10.0 are unchanged from 0.8.1.

On Windows, cuSPARSELt 0.10.0 uses ``cusparseLt_13.dll`` instead of
``cusparseLt.dll``. Loading this DLL requires ``cuda-pathfinder>=1.8.3``.
See the `cuSPARSELt release notes
<https://docs.nvidia.com/cuda/cusparselt/release_notes.html>`_ for compatibility
details, including the removal of CUDA 12.9 support in 0.9.0.

Enums and constants
*******************

.. autosummary::
   :toctree: generated/

   ComputeType
   MatDescAttribute
   MatmulAlg
   MatmulAlgAttribute
   MatmulDescAttribute
   MatmulMatrixScale
   PruneAlg
   Sparsity
   SplitKMode
   cuSPARSELtError

Functions
*********

.. autosummary::
   :toctree: generated/

   check_status
   dense_descriptor_init
   destroy
   get_error_name
   get_error_string
   get_mat_desc_attribute_dtype
   get_matmul_alg_attribute_dtype
   get_matmul_desc_attribute_dtype
   get_property
   get_version
   init
   mat_desc_get_attribute
   mat_desc_set_attribute
   mat_descriptor_destroy
   matmul
   matmul_alg_get_attribute
   matmul_alg_selection_destroy
   matmul_alg_selection_init
   matmul_alg_set_attribute
   matmul_desc_get_attribute
   matmul_desc_set_attribute
   matmul_descriptor_destroy
   matmul_descriptor_init
   matmul_get_workspace
   matmul_plan_destroy
   matmul_plan_init
   matmul_search
   sp_mma_compress
   sp_mma_compress2
   sp_mma_compressed_size
   sp_mma_compressed_size2
   sp_mma_prune
   sp_mma_prune2
   sp_mma_prune_check
   sp_mma_prune_check2
   structured_descriptor_init
