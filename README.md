# Development Setup

-   **Install the dev. environment, one-stop:**

    ```bash
    mamba env create -f ism3d.yaml
    # or
    mamba create -n ism3d
    mamba env update -f ism3d.yaml
    ```

-   **Activate the environment:**

    ```bash
    conda activate ism3d
    ipython
    ```

-   **Deactivate and remove the environment:**

    ```bash
    conda deactivate
    conda env remove -n ism3d
    ```
