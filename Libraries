// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

library Math {

    function plus(uint x, uint y) public pure returns(uint){
        return x+y;
    }

    function minus(uint x, uint y) public pure returns(uint){
        return x-y;
    }

    function multi(uint x, uint y) public pure returns(uint){
        return x*y;
    }

    function divide(uint x, uint y) public pure returns(uint){
        require(y != 0, "y can not be zero");
        return x/y;
    }

    function min(uint x, uint y) public pure returns(uint){
        if(x>=y) {
            return y;
        }
        else {
            return x;
        }
    }
}

contract Library{

    function trialPlus(uint x, uint y) public pure returns(uint){
        return Math.plus(x, y);
    }

    function trialMinus(uint x, uint y) public pure returns(uint){
        return Math.minus(x, y);
    }

    function trialMulti(uint x, uint y) public pure returns(uint){
        return Math.multi(x, y);
    }

    function trialDivide(uint x, uint y) public pure returns(uint){
        return Math.divide(x, y);
    }

    function trialMinimum(uint x, uint y) public pure returns(uint){
        return Math.min(x, y);
    }

}
