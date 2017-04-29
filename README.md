# KPTI
Katib's Pashto Text Imagebase (KPTI) is the first real dataset for the Pashto language in the field of OCR.
The KPTI contains 1,026 images. All the images are acquired by scanning with a resolution of 300dpi (dots per inch). Each scanned image is then named as Prefix-XXXX.jpg, where Prefix is describing the short name of the source book and XXXX is a number, which indexes a certain page in that book. Then text lines are extracted from the image and each text line image is then referred as Prefix-XXXX-YYY.jpg. Now, YYY represents a certain line in a page number XXXX, which is taken from the source book, that is identified by Prefix. The KPTI thus contains a total of 17,015 images of Pashto text lines. Currently, the ground truths are only available for text line's images. The file, which contains ground truth for a certain text line, is named as Prefix-XXXX-YYY.gt.txt. The ground-truth for these text images are in utf-8 codecs. The overall characters/ symbols exist in the KPTI are 96, include all Pashto basic characters, numerals, punctuation etc.

This data named KPTI is protected by copyright laws.
In case of research publication, please cite the following work.
Ahmad, Riaz, et al. "KPTI: Katib's Pashto Text Imagebase and Deep Learning Benchmark." Frontiers in Handwriting Recognition (ICFHR), 2016 15th International Conference on. IEEE, 2016.

or add this to your bib file...

@inproceedings{ahmad2016kpti,
  title={KPTI: Katib's Pashto Text Imagebase and Deep Learning Benchmark},
  author={Ahmad, Riaz and Afzal, M Zeshan and Rashid, S Faisal and Liwicki, Marcus and Breuel, Thomas and Dengel, Andreas},
  booktitle={Frontiers in Handwriting Recognition (ICFHR), 2016 15th International Conference on},
  pages={453--458},
  year={2016},
  organization={IEEE}
}

