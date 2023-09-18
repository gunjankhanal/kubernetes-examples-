![image](https://github.com/gunjankhanal/kubernetes-examples-/assets/20742236/950cb72d-0647-40e6-9221-91480a99b179)

![image](https://github.com/gunjankhanal/kubernetes-examples-/assets/20742236/fb263c57-f26e-474c-89ce-f92e86a2353d)
# Set Context to Pavan
![image](https://github.com/gunjankhanal/kubernetes-examples-/assets/20742236/d0bee389-b371-4763-a7cd-dc629d156cba)
# Now Create a Role pod-reader
# kubectl api-resources -o wide | grep pod
![image](https://github.com/gunjankhanal/kubernetes-examples-/assets/20742236/b9de18df-65fc-4932-950a-d44ac55efead)

![image](https://github.com/gunjankhanal/kubernetes-examples-/assets/20742236/425531c0-b869-468d-9367-e562852af9be)

Create Role-Binding
![image](https://github.com/gunjankhanal/kubernetes-examples-/assets/20742236/a278cfc5-69fd-449a-b481-708a9df866f8)

![image](https://github.com/gunjankhanal/kubernetes-examples-/assets/20742236/7ac05416-6f47-480a-af2f-bf582542d4be)

![image](https://github.com/gunjankhanal/kubernetes-examples-/assets/20742236/7c88f4a1-f624-4fa4-848c-eefff9d5cde5)

![image](https://github.com/gunjankhanal/kubernetes-examples-/assets/20742236/8eb6a69a-3ebf-45ba-a239-5b688f8766c5)

# Role Binding is Namespace based whereas the Cluster-Role Binding is not the Namespace Based

![image](https://github.com/gunjankhanal/kubernetes-examples-/assets/20742236/d4d50307-17ef-4560-97c9-6b7959bcaa02)

# Now Let us Create a CLuster Role Binding, 
# After this pavan user can easily access the pods for all the cluster with any namespace, and he can switch between the namespaces
# That means now pawan can easily see the list of pods in different namespaces too.
![image](https://github.com/gunjankhanal/kubernetes-examples-/assets/20742236/4ae3c8d1-de20-4b52-a1b8-860caa48d1b6)

# Now If we have mass of users then, we use the group section while creating cluster-role binding.

![image](https://github.com/gunjankhanal/kubernetes-examples-/assets/20742236/4583371c-1efd-4070-bb2a-c8559d75def7)

![image](https://github.com/gunjankhanal/kubernetes-examples-/assets/20742236/8466008d-f994-4fb0-a672-a91a61a5d5f5)
# Service Account
![Uploading image.png…]()

