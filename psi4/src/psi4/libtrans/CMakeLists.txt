list(APPEND sources
  fcidump_helper.cc
  integraltransform.cc
  integraltransform_dpd_id.cc
  integraltransform_moinfo.cc
  integraltransform_oei.cc
  integraltransform_sort_mo_tpdm.cc
  integraltransform_sort_so_tei.cc
  integraltransform_sort_so_tpdm.cc
  integraltransform_tei.cc
  integraltransform_tei_1st_half.cc
  integraltransform_tei_2nd_half.cc
  integraltransform_tpdm.cc
  integraltransform_tpdm_restricted.cc
  integraltransform_tpdm_unrestricted.cc
  mospace.cc
  )
psi4_add_module(lib trans sources)
