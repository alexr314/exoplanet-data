### Exoplanet Data

#### Ariel Dataset

This is the dataset used in the following papers:

- Anomaly Detection... (add citation)
- Others...

The data in the `ariel_dataset` folder is generated using TauREx, it has no noise added.

## Clone to get the data

To clone this repository and ensure large files are downloaded (we use Git LFS for the dataset):

1. Install Git LFS: follow https://git-lfs.github.com/ or use Homebrew (macOS):

	brew install git-lfs

2. Clone the repo and fetch LFS objects:

	git clone https://github.com/alexr314/exoplanet-data.git
	cd exoplanet-data
	git lfs install
	git lfs pull

This will place the `spectra.csv` dataset under `ariel_dataset/`.