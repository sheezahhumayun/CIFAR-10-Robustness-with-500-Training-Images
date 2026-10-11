# CIFAR-10 Robustness with 500 Training Images

## Run in Google Colab
1. Open https://colab.research.google.com and choose **File → Upload notebook**.
2. Select `CIFAR10_Section_B_Q1.ipynb`.
3. Go to **Runtime → Change runtime type**, select **T4 GPU**, and click **Save**.
4. Go to **Runtime → Run all**. The full run takes about 20–40 minutes.
5. When the last cell finishes, `Section_B_Q1_Summary.docx` is downloaded automatically. It is also saved in the Colab file panel on the left.

No extra installs are needed. CIFAR-10 is downloaded automatically by the notebook.

## Run locally (optional)
```bash
pip install torch torchvision scikit-learn pandas matplotlib python-docx jupyter
jupyter notebook CIFAR10_Section_B_Q1.ipynb
```
Then run all cells. A GPU is recommended.
