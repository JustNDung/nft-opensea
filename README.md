# NFT Marketplace with OpenSea

Dự án NFT Marketplace sử dụng Next.js, Hardhat, và Tailwind CSS v4.

## Yêu cầu hệ thống

- Node.js >= 18
- npm hoặc yarn

## Cài đặt và khởi tạo

1. **Cài đặt dependencies:**
   ```bash
   npm install --legacy-peer-deps
   ```

2. **Chạy development server:**
   ```bash
   npm run dev
   ```

3. Mở [http://localhost:3000](http://localhost:3000) để xem kết quả.

## Công nghệ sử dụng

- **Frontend:** Next.js 16, React 19, Tailwind CSS v4
- **Smart Contracts:** Hardhat, OpenZeppelin Contracts, Ethers.js v6
- **IPFS:** ipfs-http-client
- **Wallet:** Web3Modal

## Lệnh hữu ích

- `npm run dev` - Chạy development server
- `npm run build` - Build production
- `npm run start` - Chạy production server
- `npm run lint` - Chạy ESLint

## Cấu hình Tailwind CSS

Dự án sử dụng Tailwind CSS v4. Cấu hình trong `app/globals.css`:
- Import Tailwind
- Theme tùy chỉnh với `@theme inline`

Không cần file `tailwind.config.js` cho setup cơ bản.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
