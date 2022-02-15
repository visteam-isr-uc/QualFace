# Protocols

Each protocol is comprised from several .csv files:

dataset.csv - relative filenames of images used in the protocol
labest.csv - corresponting numerical labels of the images from "dataset.csv". Size is equal to the size of "dataset.csv"

protocol.csv - list of numerical pairs. Each numerical value corresponds to the index of the filename from dataset.csv.
protocol_by_names.csv -  list, which is similar to the "protocol.csv". Numericals are replaces with corresponding filenames.
cross_labels.csv - cross labels of the protocol pairs. 0 - non match; 1 - match. Size is equal to the size of "protocol.csv"
cross_labels_by_names.csv -  0 and 1 are replaced with string "nonmatch" and "match", Size is equal to the size of "protocol.csv".

