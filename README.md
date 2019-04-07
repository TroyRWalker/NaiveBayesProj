# Networks Research - Naive Bayes
Sources:
https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html
https://jakevdp.github.io/PythonDataScienceHandbook/05.05-naive-bayes.html
https://hackernoon.com/implementation-of-gaussian-naive-bayes-in-python-from-scratch-c4ea64e3944d
https://www.datacamp.com/community/tutorials/naive-bayes-scikit-learn
https://github.com/chadlimedamine/kdd-cup-99-Analysis-machine-learning-python/blob/master/kdd_binary_classification_naive_bayes.py
https://github.com/jadianes/kdd-cup-99-spark
https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html


Attributes found in the dataset (41 of them!)
duration: continuous.
protocol_type: symbolic.
service: symbolic.
flag: symbolic.
src_bytes: continuous.
dst_bytes: continuous.
land: symbolic.
wrong_fragment: continuous.
urgent: continuous.
hot: continuous.
num_failed_logins: continuous.
logged_in: symbolic.
num_compromised: continuous.
root_shell: continuous.
su_attempted: continuous.
num_root: continuous.
num_file_creations: continuous.
num_shells: continuous.
num_access_files: continuous.
num_outbound_cmds: continuous.
is_host_login: symbolic.
is_guest_login: symbolic.
count: continuous.
srv_count: continuous.
serror_rate: continuous.
srv_serror_rate: continuous.
rerror_rate: continuous.
srv_rerror_rate: continuous.
same_srv_rate: continuous.
diff_srv_rate: continuous.
srv_diff_host_rate: continuous.
dst_host_count: continuous.
dst_host_srv_count: continuous.
dst_host_same_srv_rate: continuous.
dst_host_diff_srv_rate: continuous.
dst_host_same_src_port_rate: continuous.
dst_host_srv_diff_host_rate: continuous.
dst_host_serror_rate: continuous.
dst_host_srv_serror_rate: continuous.
dst_host_rerror_rate: continuous.
dst_host_srv_rerror_rate: continuous.


In this Dataset there are 23 classes. Only one of those classes is a normal connection and the other 22 classes are different variations of malicious connections (attacks).
The names of classes are enumirated below :
1- normal 2- back 3- buffer_overflow 4- ftp_write 5- guess_passwd 6- imap 7- ipsweep 8- land 9- loadmodule 10- multihop 11- Neptune 12- nmap 13- perl 14- phf 15- pod 16- portsweep 17- rootkit 18- Satan 19- smurf 20- spy 21- teardrop 22- warezclient 23- warezmaster
