┌─────────────────────────────────────────────────────────────────────────┐
│                          USER INPUT LAYER                               │
│  📷 Tray Photo/Video  │  🏷️ Label Photo  │  📄 Menu PDF / Supplier Doc │
└──────────┬──────────────────────┬────────────────────────┬──────────────┘
           │                      │                        │
           ▼                      ▼                        ▼
┌─────────────────┐  ┌──────────────────────┐  ┌─────────────────────────┐
│  Computer Vision │  │   OCR + NLP Engine   │  │  Document Understanding │
│  • Object Detect │  │  • Text Extraction   │  │  • Table Parsing        │
│  • Segmentation  │  │  • Ingredient NER    │  │  • Ingredient Linking   │
│  • Depth / Size  │  │  • Allergen Matching │  │  • Recipe Decomposition │
└────────┬────────┘  └──────────┬───────────┘  └────────────┬────────────┘
         │                      │                           │
         └──────────────────────┼───────────────────────────┘
                                ▼
              ┌──────────────────────────────────┐
              │   🧠 Knowledge Synthesis Engine   │
              │  • Allergen–Ingredient Graph      │
              │  • Cross-Contamination Model      │
              │  • Nutritional Estimation         │
              │  • Uncertainty Quantification     │
              └──────────────────┬───────────────┘
                                 │
         ┌───────────────────────┼───────────────────────┐
         ▼                       ▼                       ▼
┌─────────────────┐  ┌─────────────────────┐  ┌─────────────────────────┐
│  🚦 Scan Results │  │  🪪 Allergen Cards   │  │  📊 Dashboard & Logs    │
│  Color-coded     │  │  Printable / QR      │  │  Nutrition summaries    │
│  badges, swaps,  │  │  for kitchen staff   │  │  Exposure history       │
│  explanations    │  │                      │  │  Analytics for admins   │
└─────────────────┘  └─────────────────────┘  └─────────────────────────┘