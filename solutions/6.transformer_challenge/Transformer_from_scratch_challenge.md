**Challenge: Build Your Own Transformer from Scratch**

**Overview**
In this challenge, you’ll dive deep into the inner workings of modern NLP architectures by implementing a Transformer model entirely from first principles. Over the course of 5 days, you’ll design, code, train, and evaluate your own Transformer on a small-scale sequence modeling task of your choice. This is your opportunity to demonstrate both your coding skills and your understanding of attention mechanisms, positional encodings, multi-head attention, and the encoder–decoder paradigm.

---

## Objectives

* **Implementation**: Write clean, modular Python code that implements all key Transformer components—scaled dot-product attention, multi-head attention, positional encodings, layer normalization, feed-forward networks, encoder and decoder blocks—from scratch (i.e., without using high-level libraries’ built-in Transformer classes).
* **Training & Inference**: Train your model on a dataset you select (e.g., character-level language modeling, simple machine translation with a small bilingual corpus, or sequence classification). Provide scripts to run both training and inference.
* **Evaluation**: Evaluate your model’s performance using standard metrics (e.g., perplexity, BLEU, accuracy), and **add your own custom evaluation** (e.g., attention-map visualizations, qualitative examples, error analysis).
* **Reporting**: Document your design choices, training setup, hyperparameters, challenges encountered, and insights in a concise report.

---

## Timeline

| Day | Milestone                                          |
| --- | -------------------------------------------------- |
| 1   | Select task & dataset; sketch model structure      |
| 2   | Implement core components (attention, encoders)    |
| 3   | Complete full encoder & decoder; add training loop |
| 4   | Train & debug; perform baseline evaluations        |
| 5   | Finalize report; package code & submit             |

---

## Deliverables

1. **Code Submission**

   * A Git repository (public or private) containing:

     * All source code for your Transformer implementation
     * A `README.md` with setup instructions and examples of how to run training/inference
     * Scripts or notebooks demonstrating training and evaluation

2. **Written Report** (PDF, max. 8 pages)

   * **Introduction & Task Definition**: What problem you chose and why
   * **Model Architecture**: Diagrams and explanations of each module
   * **Training Details**: Dataset description, preprocessing steps, hyperparameters
   * **Quantitative Evaluation**: Metrics results and comparison to any baselines
   * **Custom Analysis**: Your own insights (e.g., attention heatmaps, challenging examples)
   * **Challenges & Future Work**: What you found hard and possible extensions

---

## Evaluation Criteria

| Aspect                                                  | Weight |
| ------------------------------------------------------- | :----: |
| Correctness of Implementation (attention, layers, etc.) |   40%  |
| Code Quality & Reproducibility                          |   30%  |
| Quantitative Performance (metrics)                      |   20%  |
| Clarity & Professionalism of Report                     |   10%  |

> **Tip:** Beyond numeric scores, we’ll look for thoughtful analyses—e.g., how attention heads behave, failure cases, or novel tweaks to the standard Transformer.

---

## Rules & Guidelines

* **Frameworks Allowed:** You may use basic tensor libraries (e.g., PyTorch, TensorFlow) but **must not** use any high-level Transformer classes (e.g., `nn.Transformer`).
* **External Code:** All core Transformer logic must be your own. You may reference papers and official documentation but please cite them.
* **Submission Deadline:** End of Day 5 at 4:00 pm.
* **Honor Code:** Plagiarism or copying full solutions from the web is prohibited; let us see your search skills.

---

Good luck, and may your attention mechanisms be ever sharp!
