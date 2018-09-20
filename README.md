# CCBC Staking and Masternode
*These guides are designed to assist you in installing and configuring an CCBC staking wallet or CCBC masternode.* 

## Requirements

### Staking
  * The CCBC coins you intent to stake must have 101 confirmations
  * At least 25GB of free space
  * Synchronized CCBC wallet

### Masternode
  * Exactly 25000.00 CCBC as collateral
  * An internet addressable IP addres
  * At least 25GB of free space
  * Synchronized CCBC wallet
  
## Recommendations

### Staking
  * At least 25000 CCBC, anything less than that you are better off running a masternode
  * Dedicated machine for your wallet, as you want to keep it online as much as possible
  
### Masternode
  * Dedicated Linux (Ubuntu 16.04) VPS from [Vultr](https://www.vultr.com/?ref=7424168) 

## Staking Installation Types

### Windows

[Windows Staking Guide](Staking_for_Windows.md)

### Linux

[Linux Staking Guide](Staking_for_Linux.md)
  
## Masternode Installation Types

### Upgrading an existing installation for the mandatory network upgrade (v3.1.0)

[v3.1.0 Upgrade Guide](v3.1-UPDATE.md)

### Windows Wallet with Linux VPS
*Choose this installation guide if you are running a Windows IPSUM wallet holding the collateral for your masternode*

#### Cold Wallet
*Collateral coins are not stored on the masternode, rather in a Windows wallet.*

[Windows Wallet - Linux VPS MN](Windows_Wallet-Linux_VPS_MN-Complete.md)

### Linux Wallet and VPS
*Choose this installation guide if you are running a Linux wallet holding the collateral for your masternode*

#### Hot Wallet
*This is for advanced users and should not be used unless you understand what you are doing. Collateral coins are stored on the masternode.*

[Linux VPS Hot Wallet Installation Guide](LINUX-HOT.md)

#### Cold Wallet
*Collateral coins are not stored on the masternode, rather in a Linux wallet.*

[Linux VPS Cold Wallet Installation Guide](LINUX-COLD.md)

### Docker
*Choose this installation if your are a power user with Docker*

[Docker Installation Guide](DOCKER.md)
