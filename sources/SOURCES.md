# Source references and scenario provenance

- ECB Data Portal, AAA euro-area government bond zero-coupon yield curves: https://data.ecb.europa.eu/data/datasets/YC
- ECB SDMX data API: https://data-api.ecb.europa.eu/service/data/YC
- Reference date in provided Colab results: **19 November 2026**. ECB spot rates use continuous compounding.
- The archived tables are generated from the spot rates represented in the user's Colab screenshots and the model's synthetic portfolio specifications. The ECB curve has not been independently re-fetched during final packaging. Rounding displayed inputs may create negligible differences from a fresh download.
- All bonds and zero-coupon hedges are hypothetical, and curve shocks are constructed scenarios, not historical moves.
- Portfolio summary, scenario results and hedge sizing are included as CSV in `data/`. A full rerun in Colab will download the then-latest data and recalculate results.
