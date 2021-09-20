# denovoTE
Using ML to discover de novo transposable elements in genomic data


# Data:
Overall:
Image with visualization of DNA sequence reads aligned to a reference genome. Base pairs that match the reference genome are gray. Segments of reads that match a different chromosome are a different color mapping to the other chromosome. Single mutations are a different color too.

False positives:
Ie, images where the transposable element (colored segments indicating as such) in the proband (child, top band) are also seen in one or both parents (second and third bands). These were manually selected out of the images created. The images themselves reflect the locations in the genome where the xTea software infers there is a significant chance it contains a de novo transposable element mutation.

True positives:
Generated data. Using output from the xTea data, a TE (transposable element) mutation in a child was paired with a different set of parents. The data from the alternate set of parents was further assessed to minimize any chance that there is any activity, to enhance the image to appear as a true positive TE.
