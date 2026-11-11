# Project 3: Thought Cascade

Updated 9 November 2026. The student notebook has six function blanks and three written-answer cells. The supplied buggy function and example tests are visible before execution; experiment results are blank. Grading totals 100: Q1 (15), Q2 (10), Q3 (10), Q4 (10), Q5 (10), Q6 (45).

The notebook contains all instructions, six function exercises and three written answers. Students work in [`p03_Thought_Cascade.ipynb`](p03_Thought_Cascade.ipynb) and submit **one PDF**. A read-only [`p03_Thought_Cascade.pdf`](p03_Thought_Cascade.pdf) preview and a 2-page companion [`Project3_Student_Guide.pdf`](Project3_Student_Guide.pdf) field guide (covering workflow, mental models, and common contract pitfalls without spoilers) are included alongside the notebook. Keep the completed `.ipynb` and JSON log as backups; no separate report is required.

Open https://colab.research.google.com/, choose **File > Upload notebook**, select `p03_Thought_Cascade.ipynb`, and choose **Runtime > Change runtime type > T4 GPU**. Run setup, then work through Q1-Q6 in order. Helpers, fixtures and three illustrations are embedded; no separate upload, token or paid API is needed. Free GPU availability varies. If no GPU is available, run the deterministic checks and ask staff for recorded results; label them as recorded.

The supplied model is Qwen3-1.7B with 4-bit NF4, double quantization and FP16 compute. Thinking stays off. Keep the pinned revision, seeds 11/22/33 and supplied sampling settings. The required experiment uses at most 57 model calls. Allow about 10-15 minutes for setup and execution; this does not include implementation or analysis time. Python functions, loops, lists, dictionaries and reading exceptions are prerequisites. Lecture 17 introduces prompts, tools and observations; the notebook includes a worked controller trace.

Complete the functions in notebook cells. Setup replaces extracted helpers each time it runs. Locally, these files are in `.thought_cascade/`; in Colab, `/content/thought-cascade/`. To run locally, install PyTorch, Jupyter and `requirements.txt` in the kernel environment. Generation supports CUDA or Apple Silicon MPS. The local validation used PyTorch 2.11.0, Transformers 4.57.3 and bitsandbytes 0.50.2; Colab uses bitsandbytes 0.48.2. The code runner is not a security sandbox; use a disposable runtime without secrets or a Drive mount.

To submit, save/download the completed notebook, run the final print-export cell, then open the HTML in Chrome and choose **Print > Save as PDF**. In Colab, select the saved notebook when prompted. The export retains instructions, graded code, answers, tables, figures and code comparisons, while omitting supplied setup and execution code. Inspect the PDF and name it `LastName_FirstName_Project3.pdf`.

An unchanged or unsuccessful patch can still support a strong analysis. Full credit does not require a positive feedback effect. Do not rerun until a preferred result appears.
