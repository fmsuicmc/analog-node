<img width="673" alt="Screenshot 2024-06-09 at 1 30 49 AM" src="https://github.com/zircuit-labs/ceremony/assets/106862644/190695e3-6669-48bd-848e-482d86d59b23">



Run a  Node analog with One Command

``` 
1- Social task LINK : https://testnet.analog.one/#/?signup&referral=L9FW4S
``` 

2- node 

``` 
sudo apt install apt-transport-https ca-certificates curl software-properties-common -y && curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - && sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable" && sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin -y

```
<img width="673" alt="Screenshot 2024-06-09 at 1 33 07 AM" src="https://github.com/zircuit-labs/ceremony/assets/106862644/26cc9ae0-c76a-4eda-9190-ddb30fee8f98">



``` 
docker pull analoglabs/timechain

```

<img width="673" alt="Screenshot 2024-06-09 at 1 33 53 AM" src="https://github.com/zircuit-labs/ceremony/assets/106862644/2a46967f-c111-4fee-984a-e217b662f6d7">



```
docker run -d -p 9944:9944 -p 30403:30303 -v $(pwd)/.analog:/.analog --name analog analoglabs/timechain --base-path /.analog --rpc-external --rpc-methods=Unsafe --unsafe-rpc-external --name YOUR_NAME_NODE

```


```
docker logs analog

```

<img width="673" alt="Screenshot 2024-06-09 at 1 35 21 AM" src="https://github.com/zircuit-labs/ceremony/assets/106862644/d283b297-9ec1-42a5-bc54-9774c2ac1820">


save data node and fill form : https://l5d87lam6fy.typeform.com/to/kwlADm6U

.
.

my chanel :

https://t.me/Fmusicmc_P

https://x.com/mr_satoshiii

