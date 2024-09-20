# S&UI Dataset

Welcome to the **S&UI Dataset** repository, which provides semantic information extracted from mobile UI screenshots as part of our research on **Leveraging Multimodal LLM for Inspirational User Interface Analysis**.

## Repository Structure

The repository contains three folders, each representing a different dataset used in our research. Inside each folder, you will find a `.tar.gz` file containing YAML-formatted semantic data extracted using our multimodal LLM pipeline. Below is a description of each folder and the datasets they contain:


### 1. Mobbin
- This folder includes semantic extractions from the **Mobbin dataset**.
- **Note**: The original images are not included due to intellectual property concerns. However, the YAML files containing the semantic annotations are available in the `.tar.gz` archive.
  **Future Release**: The 10k version of the Mobbin dataset, which was used in the comparative study with designers, may be released later.

### 2. SCapRepo
- This folder contains the semantic extractions from the **SCapRepo dataset**.
- The YAML files are compressed into a `.tar.gz` archive and are linked to the original SCapRepo dataset images by filename.

### 3. Enrico
- This folder contains semantic extractions from the **Enrico dataset**.
- As with SCapRepo, the YAML files are compressed in a `.tar.gz` file and are associated with the original Enrico dataset images by their filenames.

## Usage

To access the semantic data, download the `.tar.gz` files from the respective folders and extract them. The extracted YAML files will be organized by the original image names, allowing you to map them to the respective images from the original datasets (SCapRepo and Enrico) if you have access.

### Example Workflow
1. Download the `.tar.gz` file from the desired folder.
2. Extract the contents using:
   ```bash
   tar -xvzf <filename>.tar.gz
   ```
3.	Match the YAML file names with the corresponding image filenames in the original dataset.

## Acknowledgments

We would like to thank the creators of the **[SCapRepo dataset](https://github.com/Jl-wei/guing)** and the **[Enrico dataset](https://github.com/luileito/enrico)** for making their datasets available and supporting the research community. Please refer to their respective licenses and terms of use for any restrictions or guidelines regarding their data.
Additionally, we acknowledge the **Mobbin** for providing screenshots, and we aim to release the 10k version of this dataset, used in our comparative study with designers, in the future after discussing IP considerations.
