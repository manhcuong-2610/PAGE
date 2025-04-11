---
title: "Text classification for museum records"
date: 2025-02-28
collection: projects
permalink: /projects/2025-02-28-projectTA/
excerpt: "Text analytics project"
notebook_url: "/PAGE/files/Text.html"
---
## Overview

This project focused on developing a multi-class classifier to automatically assign museum records to one of five institutions. 
Leveraging a labelled dataset spanning training, validation, and test sets, I performed detailed data cleaning, exploration, and tokenization to prepare the text for model training. 
I experimented with three large language model (LLM) prompt templates assessing accuracy, macro precision, macro recall, and macro F1 before fine-tuning a transformer model (using 'bert-base-uncased' and other variants) with hyperparameter tuning. 
Identifying and correcting issues in the validation set was crucial for improving model performance. Ultimately, I selected and deployed the best-performing ('distilbert-base-uncased') model based on macro-F1, demonstrating robust accuracy, precision, recall, and F1 on the test set.

**My Colab notebook:** [Click here to view the notebook]({{ page.notebook_url }})
