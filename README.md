# Remote-jupyter
#### Run jupyter on server and access it on local browser
<hr/>

#### Merajs-MacBook-Air:~ merajahmed$ ssh merajahmed@10.237.22.140

#### merajahmed@vindhya:~$ jupyter notebook --no-browser --port=8889

#### Merajs-MacBook-Air:~ merajahmed$ ssh -N -f -L localhost:8888:localhost:8889 merajahmed@10.237.22.140
