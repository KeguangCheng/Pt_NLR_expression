# Analysis Code

These R Markdown files split the original `final_keguang_clean.Rmd` into runnable analysis modules.

Run the files in numeric order. Each module writes reusable tables or cached RDS objects for downstream modules. Expensive steps are cached under `../RData` when possible.

`final_keguang_clean.Rmd` is not modified.
