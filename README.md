# Masternode Setup Guide

wget -q https://raw.githubusercontent.com/UfyCoin/MN_Script/blob/master/masternodeinstall.sh

sudo chmod +x masternodeinstall.sh

./masternodeinstall.sh

When prompted to Enter your UnifyCoin Masternode GEN Key.

Paster your Masternode GEN Key and press enter

Wait till Node is fully Synced with blockchain. For check enter below command.

ufy-cli getinfo

When Node Fully Synced enter below command for check masternode status.

ufy-cli masternode status
