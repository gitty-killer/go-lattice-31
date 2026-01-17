# go-lattice-31

A small Go tool that computes text statistics for lattice.

## Goal
- Provide quick text metrics for lattice documents.
- Report top word frequencies for fast inspection.

## Usage
go run main.go data/sample.txt --top 5

## Output
- lines: total line count
- words: total word count
- chars: total character count
- top words: most frequent tokens (case-insensitive)

## Notes
- Only ASCII letters and digits are treated as word characters.
