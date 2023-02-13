# Aminoacid Pairwise Alignmenter

This script provides a simple and easy-to-use tool for performing sequence alignments between two amino acid sequences. The tool supports three different algorithms (Smith-Waterman, Needleman-Wunsch, and BLAST), and provides visual and export options for the results.

## Requirements

-   Python 3.x
-   argparse
-   matplotlib
-   numpy

## Usage

The script is executed from the command line, and requires the following arguments:

    --sequence1: The first amino acid sequence
    --sequence2: The second amino acid sequence
    --algorithm: The algorithm to use for the alignment (Smith-Waterman, Needleman-Wunsch) 

Additionally, the following optional arguments are supported:

    --gap_penalty: The gap penalty to use for the alignment (default: -1)
    --scoring_matrix: The scoring matrix to use for the alignment (default: BLOSUM62)

## Visualizing Results

The results of the alignment are visualized using the `matplotlib` library. A grayscale image is generated, where darker regions indicate higher scores.

## Exporting Results

The results of the alignment can be exported in a variety of formats (e.g., CSV, Excel, etc.). Currently, this functionality is not implemented, but can be added in the future.

## Contributing

If you would like to contribute to this project, please feel free to submit a pull request or reach out for more information.

## License

This project is licensed under the MIT License.
