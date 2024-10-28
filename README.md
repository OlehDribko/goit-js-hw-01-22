function makeTransaction (quantity, pricePerDroid){
    const totalPrice = quantity * pricePerDroid;
return `You ordered ${quantity} droids worth ${totalPrice} credits!`
}
function getShippingMessage(country, price, deliveryFee) {
    
    const totalPrice = price + deliveryFee
    
        return `Shipping to ${country} will cost ${totalPrice} credits`;
    }
function getElementWidth(content, padding, border) {
    

return parseFloat(content) + (parseFloat(padding) + parseFloat(border)) * 2;
    
}
