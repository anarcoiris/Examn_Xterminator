### Examn Xterminator

## Requirements:
pip install pymupdf Pillow pytesseract requests rapidfuzz
setx OPENAI_API_KEY (your api key)

## How to use:
python pdf_exam.py --pdf /route/to/your_merged_examns.pdf --out ./"folder name" --sleep (streaming delay in seconds. default is 1. Used 5 with caution and great results)
python autolatex.py --md "./folder/solutions.md" --out your_output.tex --title "Exámenes de... (whatever)"


## To-Do Ideas:
Adding index (and curate the section, subsection, etc...)
Adding resume
Analize by examn structure (instead of pages)
Checking for multiple languages
PDF compiler + Unified scripts (im using overleaf for now)
Embedding in a LaTeX template
...
GUI, TTS integration...
