# Genesisnode
GenesisNodePOSist
Solution for POSist coding test



1.Create the Genesis Node. Genesis Node has parent node as null.<br>
2.Create set of child nodes of a particular node.<br>
3.Create a child node that originates from a particular node.<br>
4.Encrypt and decrypt the data inside the node<br>
5Verify the owner of the node, with the encryption key. Symmetric encryption shows the data. The integrity of the data is checked by computing the hash value of the data and checking with the already computed hash.<br>
6.Edit value of a node. Editing can have many forms, edit value of a subtree root, trickle down the subtree node value to a set of children, or one child or edit value of a leaf node.<br>
7.Transfer ownership of a particular node value. The previous owner validates his/her ownership by decrypting the data, and comparing the hash values. The new owner then encrypts the data with his key.<br>
8.Find the longest chain of the genesis node.<br>
9.Find the longest chain of any node.<br>
10.Merge 2 nodes; data is added of the 2 nodes, ownership of the longer chain node are retained after a merge operation.<br>

