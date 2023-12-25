# Car Borrowing dApp built on Hedera
This is a dApp built and deployed on Hedera. This dApp facilitates the functionalities of a car borrowing platform:
- merchants can put up their vehicles for renting on the platform (vehicles are represented as NFTs)
- users can rent these vehicles (NFTs will be transferred from the merchant to the user)
- the user will have to deposit an amount of HBAR tokens for the duration of the rental period (escrow)
- once the rental period is up, the user returns the vehicle (transfers NFT back to the merchant) and gets his locked up HBAR tokens returned to him
- the merchant will assign a reputation score to the user based on how good of a customer he is (represented as fungible tokens)

Below are some images showing how the dApp looks like:

<p align="center">
  <img src="https://github.com/jameslimjy/hedera-car-borrowing-dapp/assets/56946413/bd1a1e4b-ef64-402c-af25-0bb172b64f04" alt="merchant_add_new_car"/>
  <br>
  <em>Merchant adding new car to his fleet (mints a new NFT)</em>
</p>

<p align="center">
  <img src="https://github.com/jameslimjy/hedera-car-borrowing-dapp/assets/56946413/496b9fb0-ca9b-4631-a58c-9535151213b5" alt="car_borrowing_page"/>
  <br>
  <em>Customer selects which car to borrow</em>
</p>

<p align="center">
  <img src="https://github.com/jameslimjy/hedera-car-borrowing-dapp/assets/56946413/2cde3139-e1e2-439a-98e9-b0d5c43c9387" alt="customer_lockup"/>
  <br>
  <em>Customer deposits an amount of HBAR tokens after borrowing vehicle</em>
</p>

<p align="center">
  <img src="https://github.com/jameslimjy/hedera-car-borrowing-dapp/assets/56946413/907d8895-7eb1-4d9a-a35a-cc42d65ab0e2" alt="merchant_assign_reputation_score"/>
  <br>
  <em>Merchant assigns reputation score to customer</em>
</p>

<p align="center">
  <img src="https://github.com/jameslimjy/hedera-car-borrowing-dapp/assets/56946413/a9710f47-316c-4e24-8619-c049d188f9f7" alt="customer_has_reputation_score"/>
  <br>
  <em>Customer receives reputation score (fungible token) and deposited HBAR tokens</em>
</p>



