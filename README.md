# facial_keypoint_detection

The modified version is in the "fei_fkd.ipynb" file.



My modifications are as follows:

* The "show_keypoints_batch" function.
* The "class Net" structure.
* The "train_net" funtion.
* `optimizer = optim.Adam(net.parameters(), lr=0.0001)` lr have modified 0.0001.
* `n_epochs = 20`
* `train_net(net, device, criterion, optimizer, n_epochs)  `

You can check the details from the Notebook.