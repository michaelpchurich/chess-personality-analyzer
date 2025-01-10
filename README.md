# chess-personality-analyzer\\
This project analyzes chess puzzles and categorizes them based on five personality dimensions:
- Risk Taking
- Resilience
- Conscientiousness
- Endurance
- Mental Flexibility

## Setup
1. Install Python requirements:

2. pip install chess pandas tqdm2. Download Stockfish chess engine from https://stockfishchess.org/download/3. Update the Stockfish path in analyze_puzzles.py to point to your Stockfish installation## Files- analyze_puzzles.py: Main script for analyzing puzzles- view_puzzles.py: Script for viewing categorized puzzles- lichess_puzzles.csv: Input puzzle database- categorized_puzzles.csv: Output file with analyzed puzzles## Usage1. Run puzzle analysis:python analyze_puzzles.py2. View categorized puzzles:python view_puzzles.py

