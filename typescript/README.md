* Passo 1
`sudo docker build -t cores_test_node .`
* Passo 2
`sudo docker run --rm --name node_container_name --interactive --tty --cpuset-cpus="0" cores_test_node npm start`
