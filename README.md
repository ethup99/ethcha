# ethcha

// 🔧 调用方式 =getZKSyncBalance(B2, "ETH")
// 支持币种: ETH, USDC, USDT, WBTC, DAI, ZZ 等
function getZKSyncBalance(address, token) {
  if (['USDC', 'USDT'].includes(token.toUpperCase())) {
    decimal = 6;
  } 
  else {
    decimal = 18;
  }

Coming Soon
Farcaster and Lens connections
