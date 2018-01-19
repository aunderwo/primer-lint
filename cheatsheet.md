### Instructions for future me
  1. In code/python/primer-lint_test
  
  2. Extract primer sequences from primer_sequences.tab
  ```
  python extract_primers.py
  ```
  
  3. Install primer-lint if code has been edited. Within primer-lint dir
  ```
  sudo -H python setup.py install
  ```
  
  4. run primer lint
  ```
  primerlint.py --importfasta primer_sequences.fas --outputlog primer-lint.out --hairpin 8 --primerdimer 15
  ```