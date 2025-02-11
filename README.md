Code from [this](https://github.com/EdwardRaff/Inside-Deep-Learning) repository, with modifications to run in Google Colab notebooks.

## How to Use the Codes
1. Go to the [Google Colab](https://colab.research.google.com) website.
2. Log in if not already logged in.
3. On the *Welcome page* (or file -> open notebook if the window is not visible), in the *GitHub* tab, enter the URL of this repository to open a notebook.
4. *(Optional)* You can copy the notebook into your Google Drive to make changes there.
5. Choose a runtime type and press *Connect*.
   - This repository usually assumes a CUDA GPU runtime (tested with T4), unless otherwise mentioned (e.g., Chapter 8 uses TPU, tested with v2-8).
6. Go to Runtime -> Run all, or run cells one by one using `Shift` + `Enter`.

## Google Colab Considerations
1. On the free plan, you have limited runtime hours. The more you use, the fewer daily hours you get.
2. You might be able to run multiple runtimes concurrently if you're lucky, or you may need to terminate others to run a new one.
3. Although all codes finish running within the time window, make sure to connect to a runtime when you are finished editing your code.
4. Using CPU-only runtimes might give you more time, but they are painstakingly slow for deep learning tasks, especially in later chapters.
5. All codes are saved inside your Google Drive storage, in a folder called "Colab Notebooks". Minimal storage is needed as datasets are downloaded into runtime storage, not Drive storage.
6. Runtime storages are hosted within virtual machines and will be wiped upon exit. If you've created a model you're proud of, save the model in your Drive (using Drive APIs in Google Colab) or download it to your local computer.
