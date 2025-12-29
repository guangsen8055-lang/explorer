# EthExplorer (In Progress)

![EthExplorer Screenshot](http://i.imgur.com/NHFYq0x.png)

##License

GPL (see LICENSE)

##Installation

Install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git "Git installation") if you haven't already

Clone the repo

`git clone https://github.com/etherparty/explorer`

Download [Nodejs and npm](https://docs.npmjs.com/getting-started/installing-node "Nodejs install") if you don't have them

Start the program. All dependencies will be automatically downloaded

`npm start`

Then visit http://localhost:8000 in your browser of choice. You might get an error message:

`geth --rpc --rpccorsdomain "http://localhost:8000"`

Install [geth](https://github.com/ethereum/go-ethereum/wiki/Building-Ethereum "Geth install") if you don't already have it, then run the above command.

Then refresh the page in your browser 

- ## 🎨 **视觉设计**

  - **主色调**：白色/灰色 → 蓝色渐变背景（科技感）
  - **布局**：扁平设计 → 卡片式立体设计（圆角+阴影）
  - **导航栏**：黑色 → 深蓝色（与主题协调）

  ## 🔧 **功能优化**

  - **搜索框**：英文提示 → 中文提示"搜索: 交易哈希、地址或区块号"
  - **按钮**：添加图标"🔍"增强识别性
  - **信息展示**：添加节点状态显示和主题说明区域

  ## 📱 **交互体验**

  - **响应式**：优化移动端显示
  - **便捷操作**：页脚添加刷新链接
  - **视觉反馈**：蓝色边框和悬停效果

  ## 📝 **内容调整**

  - **标题**：添加"蓝色主题版"标识
  - **页脚**：扩展版权信息，添加运行环境说明
  - **提示信息**：中文为主，降低使用门槛
