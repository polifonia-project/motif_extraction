# motif_extraction
A novel local-alignment-based approach to motif extraction in polyphonic music

This work proposes a novel approach to musicologically-informed intra-opus motif detection within polyphonic music scores. We extract diatonic interval sequences from each voice of a score; sequence segmentation is performed via pairwise local alignment between each pair of voices using Smith-Waterman algorithm. From the output of this step, string-based approaches are used for motif discovery. Then a weighted directed acyclic graph is constructed, giving a custom measurement of motif importance. A selection and filtration procedure is applied according to a set of rules and music structural information, to generate a final selection of music motifs. 
