Gramik POP Intelligence - core package (24 Oct 2026)

POP_Engine.html   The final POP engine (latest published version). Open in any browser.

data/  The 10 source files the engine is built from:
  stage_plan.csv          720 crop stages (45 crops, 109 varieties): day windows, S1-S8 code, Hindi POP text, products
  stage_watch_ranked.csv  2,280 risk rows: which problems to watch at each stage, ranked H/M/L
  issue_master.csv        80 problems: English/Hindi name, symptom, favourable weather, photo part
  issue_products.csv      176 problem-to-product links (prevent / cure, main pick and backup)
  prevent_actions.csv     67 lists of preventive field steps per problem
  nutrition_options.csv   15 nutrition options by stage and crop group
  products.csv            51 products: type, technical name, dose per acre, method, Gramik yes/no
  crop_groups.csv         45 crops mapped to 22 crop groups and season
  factor_notes.csv        110 crop-group notes for the five decision areas
  kranti_label_map.csv    380 Kranti photo labels mapped to problem IDs
