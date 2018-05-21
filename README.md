# AFM-lab-analysis-tool
python utility for regressions of Atomic Force Microscopy lab at FU Berlin

"""
READ ME:
To use this program, ensure that the path points to the directory where the relevant text files reside.
It does not matter what their names are, but as all text files in a given folder will be averaged together, ensure that
only the data relevant to a given measurement (ex. task 4, Gold) is present in a given folder. The result for linear
and quadratic regressions are displayed, along with their first derivative values at 0, and a file is created where
the program runs containing the given data. Change the file_name so as not to overwrite the data each time.
Error given is the standard deviation, linear regressions are based on the first half of the data. To create regressions
without the points in the neighborhood of zero (where vanderwaals forces override those making the parabolic relation) part,
uncomment the labeled section in the first for loop
"""
