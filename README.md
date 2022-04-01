# Auction House Interview

This repo hosts our auction house interview. Please fork it and create pull requests to implement your changes for each story. When done over video chat, this interview takes about 90 minutes. 

## Stories
* [TS-001: Implement a sealed-bid auction in the TypeScript codebase](backlog/ts-001.md)
* [RUBY-001: Refactor the English auction in the Ruby codebase](backlog/ruby-001.md)

### Usage

#### Ruby Auction

```
cd ruby
bundle install
rspec
./auction
```

#### Typescript Auction

```
cd typescript
yarn global add pnpm
pnpm install
yarn test
./auction.sh
## FOR SELAED AUCTION
./sealed_auction.sh
```
