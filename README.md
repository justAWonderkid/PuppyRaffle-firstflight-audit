# What is a CodeHawks First Flight?

First Flights are 7 days long smart contracts auditing challenges characterised by smaller codebases and different rewards mechanisms from our standard smart contract auditing competitions, making them the perfect testing and learning ground for any aspirant smart contract security auditor.

# First Flight #2: PuppyRaffle

This project is to enter a raffle to win a cute dog NFT. The protocol should do the following:

• Call the enterRaffle function with the following parameters:
    address[] participants: A list of addresses that enter. You can use this to enter yourself multiple times, or yourself and a group of your friends.
• Duplicate addresses are not allowed
• Users are allowed to get a refund of their ticket & value if they call the refund function
• Every X seconds, the raffle will be able to draw a winner and be minted a random puppy
• The owner of the protocol will set a feeAddress to take a cut of the value, and the rest of the funds will be sent to the winner of the puppy.

https://www.codehawks.com/contests/clo383y5c000jjx087qrkbrj8