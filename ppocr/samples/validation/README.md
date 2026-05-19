Each standard engine has its own validation directory. The directory name matches the engine file basename.

```text
ppocrv5_mobile_det/                 ocr_text.bmp
ppocrv5_mobile_rec/                 ocr_text_line.bmp
ppocrv5_server_det/                 ocr_text.bmp
ppocrv5_server_rec/                 ocr_text_line.bmp
pp_lcnet_x1_0_doc_ori/              document_layout.bmp
pp_lcnet_x1_0_table_cls/            table_layout.bmp
pp_lcnet_x1_0_textline_ori/         ocr_text.bmp
pp_docblocklayout/                  document_layout.bmp
pp_doclayout_plus_l/                document_layout.bmp
rt_detr_l_wired_table_cell_det/     table_layout.bmp
rt_detr_l_wireless_table_cell_det/  table_layout.bmp
slanet_plus/                        table_layout.bmp
slanext_wired/                      table_layout.bmp
uvdoc/                              document_layout.bmp
pp_formulanet_plus_l/               formula_latex.bmp
pp_formulanet_plus_l.decoder/       formula_latex.bmp
```

The four root-level images are kept for compatibility with older examples and for whole-system directory validation.
