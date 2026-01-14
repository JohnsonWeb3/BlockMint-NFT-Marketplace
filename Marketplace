// NFT.sol
pragma solidity ^0.8.0;

contract NFT {
    uint public totalSupply;
    mapping(uint => address) public ownerOf;

    function mint() public {
        totalSupply++;
        ownerOf[totalSupply] = msg.sender;
    }
}
