# homebrew
解决因为nds屏蔽而无法安装homebrew,修改了安装 homebrew 的 shell
> 国内无法访问 https://raw.githubusercontent.com 因为它一并被dns劫持了，备份了home brew的安装shell文件,方便Mac用户安装homebrew使用。
> Mac有自己的软件应用商店==> App Store不过，作为开发者，有很多开源软件，在App Store里并没有。所以 homebrew 是Mac用户使用的开源软件源。类似于linux 中centOS 的yum，或Ubuntu 的apt。是对App Store的补充。


使用方法：
  将homebrew官网上的安装命令中的地址替换成本仓库中的`install.sh`
  官网中原命令为:
  ```shell
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  ```
  更换地址后为：
  ```shell
  /bin/bash -c "$(curl -fsSL https://github.com/aaroncastle/homebrew/install.sh)"
  ```
  
