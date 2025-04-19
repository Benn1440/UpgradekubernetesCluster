 # Steps to Upgrading Kubernetes Cluster Master Node
****
2. Drain Control Plane Node<br><br>
![cluster](https://github.com/user-attachments/assets/b7b7cb6a-0a12-413a-a0a8-5d374ddcc092)
3. Plan the Upgrade
4. Apply the Upgrade<br><br>
![IMG_6523](https://github.com/user-attachments/assets/dd9c0563-222b-4bf4-bbdb-a0e1091c20f3)

5. Upgrade kubectl & kubelet on control plane node<br><br>
![IMG_6525](https://github.com/user-attachments/assets/bedfae36-0163-4398-96b0-3bb2082eedd0)

6. Uncordon the Node<br><br>
![IMG_6527](https://github.com/user-attachments/assets/370ba620-9f29-4442-8a39-1af08c1c4c25)


 # Steps to Upgrading Kubernetes Cluster Worker Node

N:B: In upgrading worker nodes, ensure this is done in a rolling-upgrade manner, meaning one worker node at a time, to avoid downtime in production.

And the commands must be executed from the master Node
 ****
 2. Drain Worker Node <br><br>
![IMG_6530-images-0](https://github.com/user-attachments/assets/d3eb4572-1844-41b6-b530-bc2a4c9c3463)

 3. Upgrade kubeadm
 4. Upgrade kubelet config
 5. Upgrade kubectl and kubelet
 6. Uncordon the Node <br><br>
![IMG_6530-images-4](https://github.com/user-attachments/assets/b89b54e7-b04e-47af-81a2-8c73937b0b0b)



