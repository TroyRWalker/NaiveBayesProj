# Networks Research - Naive Bayes implementation
Sources:
<br>
https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.LabelEncoder.html
<br>
https://jakevdp.github.io/PythonDataScienceHandbook/05.05-naive-bayes.html
<br>
https://hackernoon.com/implementation-of-gaussian-naive-bayes-in-python-from-scratch-c4ea64e3944d
<br>
https://www.datacamp.com/community/tutorials/naive-bayes-scikit-learn
<br>
https://github.com/chadlimedamine/kdd-cup-99-Analysis-machine-learning-python/blob/master/kdd_binary_classification_naive_bayes.py
<br>
https://github.com/jadianes/kdd-cup-99-spark
<br>
https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html
<br>


Attributes found in the dataset (41 of them!)
<br>
duration: continuous.
<br>
protocol_type: symbolic.<br>
service: symbolic.<br>
flag: symbolic.<br>
src_bytes: continuous.<br>
dst_bytes: continuous.<br>
land: symbolic.<br>
wrong_fragment: continuous.<br>
urgent: continuous.<br>
hot: continuous.<br>
num_failed_logins: continuous.<br>
logged_in: symbolic.<br>
num_compromised: continuous.<br>
root_shell: continuous.<br>
su_attempted: continuous.<br>
num_root: continuous.<br>
num_file_creations: continuous.<br>
num_shells: continuous.<br>
num_access_files: continuous.<br>
num_outbound_cmds: continuous.<br>
is_host_login: symbolic.<br>
is_guest_login: symbolic.<br>
count: continuous.<br>
srv_count: continuous.<br>
serror_rate: continuous.<br>
srv_serror_rate: continuous.<br>
rerror_rate: continuous.<br>
srv_rerror_rate: continuous.<br>
same_srv_rate: continuous.<br>
diff_srv_rate: continuous.<br>
srv_diff_host_rate: continuous.<br>
dst_host_count: continuous.<br>
dst_host_srv_count: continuous.<br>
dst_host_same_srv_rate: continuous.<br>
dst_host_diff_srv_rate: continuous.<br>
dst_host_same_src_port_rate: continuous.<br>
dst_host_srv_diff_host_rate: continuous.<br>
dst_host_serror_rate: continuous.<br>
dst_host_srv_serror_rate: continuous.<br>
dst_host_rerror_rate: continuous.<br>
dst_host_srv_rerror_rate: continuous.<br>


In this Dataset there are 23 classes. Only one of those classes is a normal connection and the other 22 classes are different variations of malicious connections (attacks).<br>
The names of classes are enumirated below :<br>
1- normal 2- back 3- buffer_overflow 4- ftp_write 5- guess_passwd 6- imap 7- ipsweep 8- land 9- loadmodule 10- multihop 11- Neptune 12- nmap 13- perl 14- phf 15- pod 16- portsweep 17- rootkit 18- Satan 19- smurf 20- spy 21- teardrop 22- warezclient 23- warezmaster
