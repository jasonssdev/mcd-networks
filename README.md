# mcd-networks

conda env export --from-history --no-builds | sed '/^prefix:/d' > environment.yml