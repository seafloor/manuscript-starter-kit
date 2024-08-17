# manuscript-starter-kit
 A cookie-cutter repository for starting bioinformatics manuscripts with a pre-built structure and template files.

This is a minimal repo for me to pull from to streamline paper creation. It's focus is on forcing good structure in the manuscript (I suck at titles, abstract and results, so I follow [this layout](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005619), but apparently so do most of us) and stopping me from recreating code and figures I use a lot from scratch (something I do far to much). It's for me, is layed out for my authorships, figure preferences etc., and I haven't tried to make it helpful for everyone, but maybe it will be somewhat.

## Structure
- **manuscript/**
  - `manuscript_template_full.docx`: A Word template with structure set out and copious advice on nailing the hard bits at the right points, with examples
  - `manuscript_template_minimal.docx`: A Word template with structure set out and minimal advice so you can just get going
- **notebooks/**
  - `plotting_functions.ipynb`: Common plotting functions ready to use
- **tests/**
  - `test_data_processing.py`: Placeholder for data processing tests
  - `test_plotting.py`: Placeholder for plotting tests
- **src/**
  - **data/**: Simulated data to mimic the raw data so analysis scripts can run
  - **scripts/**: Custom analysis scripts, with example simulate.py or simulate.R for making the dummy data
  - **figures/**: Store your generated figures here

## Instructions
1. Clone the repository: `git clone https://github.com/yourusername/manuscript-starter-kit.git`
2. Replace the template files with your content.
3. Use the Jupyter notebook for plotting and analysis.
4. Run tests to ensure your functions work as expected.

## License
This repository is licensed under the MIT License.
