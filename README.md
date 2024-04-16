# subquery.github.io
abap with subquery


# Main Page

This is main Page


```abap
selection-screen begin of block b01 with frame title text-t01.

  select-options: s_werks for ekpo-werks obligatory memory id wrk,
                  s_lgort for ekpo-lgort,
                  s_matnr for mard-matnr,
                  s_mtart for mara-mtart,
                  s_matkl for mara-matkl,
                  s_bismt for mara-bismt,
                  s_bklas for mbew-bklas,
                  s_partn for but000-partner.

  selection-screen skip 1.

  parameters p_nzero type sap_bool as checkbox default abap_true.

selection-screen end of block b01.
```
