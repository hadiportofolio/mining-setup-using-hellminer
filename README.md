# mining-setup-using-hellminer
1. make start.sh : nano start.sh

2. wget https://raw.githubusercontent.com/hadiportofolio/mining-setup-using-hellminer/main/start.sh

3. chmod +x start.sh

4. make crontab - e
@reboot /root/start.sh > /root/start.log 2>&1

#download hellminer 

1. wget https://github.com/hellcatz/hminer/releases/download/v0.59.1/hellminer_linux64_avx2.tar.gz
  
3. (link : https://github.com/hellcatz/hminer/releases )

2. tar -xvzf hellminer_linux64_avx2.tar.gz

------------------------------------------------ this step is only for me beacuse its my wallet addrs 

3. rm run_miner.sh

4. wget https://raw.githubusercontent.com/hadiportofolio/mining-setup-using-hellminer/main/run_miner.sh

5. chmod +x run_miner.sh

# add step
6. nano run_miner.sh (check cpu ,addrs and server from luckpool or you can change your fav pool)

7. screen -ls (check screen run)

8. screen -r mining (to retach with screen)
