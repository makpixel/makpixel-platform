# makpixel-platform
# MakPixel - Web3 Photography Marketplace

## Overview
MakPixel is a decentralized photography platform built on Solana that enables photographers to monetize their work through blockchain technology. The platform operates a dual-payment ecosystem using MAKPIX tokens and traditional payment methods.

## Platform Features
- **Creator Economy**: Photographers earn 80% of sales revenue directly to their wallets
- **Dual Payments**: MAKPIX tokens (50% discount) + traditional payments via Ziina
- **Quality Rewards**: Automated token distribution based on upload specifications
- **Instant Settlement**: Real-time payments through Solana blockchain

## Tokenomics
- **Total Supply**: 100,000,000 MAKPIX
- **Circulating Supply**: 45,100,000 MAKPIX
- **Locked Tokens**: 54,900,000 MAKPIX (vested via Streamflow Finance)
- **Blockchain**: Solana
- **Token Standard**: SPL Token

## Technical Architecture
- **Backend**: Node.js/Express with MongoDB
- **Blockchain**: Solana integration for token transfers
- **Payment Processing**: Ziina gateway for traditional payments
- **File Storage**: Secure upload system with Sharp image processing
- **Authentication**: JWT-based user management

## API Endpoints
### Token Information
- `GET /api/token/total-supply` - Returns total token supply
- `GET /api/token/circulating-supply` - Returns circulating supply
- `GET /api/users/makpix-price` - Returns current MAKPIX price from Raydium

### Platform Operations
- `POST /api/photos/upload` - Photo upload with reward calculation
- `GET /api/photos/payment-options/:id` - Dynamic pricing for photos
- `POST /api/photos/purchase/:id` - Token-based photo purchases

## Smart Contracts
- **MAKPIX Token**: `Rt8TZokeX8vE2ftKwPH6h5DFdD7HS9SDKzysKuygfE5`
- **Vesting Contract**: `DSBtY5f6E7sKe3ZEHzC8xkuU31NAv5YQCsTb2pmqpayX` (Streamflow Finance)

## Links
- **Platform**: https://makpixel.com
- **Token Explorer**: https://solscan.io/token/Rt8TZokeX8vE2ftKwPH6h5DFdD7HS9SDKzysKuygfE5
- **Vesting Contract**: https://app.streamflow.finance/contract/solana/mainnet/DSBtY5f6E7sKe3ZEHzC8xkuU31NAv5YQCsTb2pmqpayX

## Business Model
1. **Upload Rewards**: Photographers earn MAKPIX for quality uploads
2. **Sales Revenue**: 80% to creators, 20% to platform liquidity
3. **Token Utility**: 50% discount for MAKPIX payments vs traditional methods
4. **Ecosystem Growth**: Circular economy supporting creator monetization

## Development Status
- ✅ Live platform with working payments
- ✅ Solana blockchain integration
- ✅ Dynamic pricing system
- ✅ Mobile wallet compatibility
- ✅ Quality-based reward algorithm

## Support
For technical support or partnership inquiries:
- Email: support@makpixel.com
- Platform: https://makpixel.com

---
*This repository contains public documentation for the MakPixel platform. Proprietary code is maintained privately for security purposes.*
