// React 16.x code​​​​​​‌‌‌​​‌​​​‌‌​​‌‌‌​‌‌‌‌​‌​​ below
import React from "react";
import { createGlobalStyle } from "styled-components";

// Challenge Component
export function ProductList() {
    return (
        <div>
            <h2>Software Developer Supplies 🖥️</h2>
            <ul> 
                {products.map((product) => (
                    <li key={product.id}>{product.name} - ${product.price}
                </li>
            ))}
            </ul>
            {/* Display the products as an unordered list */}
        </div>
    );
}

export const products = [
    { id: 1, name: "Mechanical Keyboard", price: 120 },
    { id: 2, name: "Noise-Canceling Headphones", price: 250 },
    { id: 3, name: "Ergonomic Chair", price: 300 },
];


function App() {
    return (
        <div className="App">
            <GlobalStyle />
            <ProductList />
        </div>
    );
}
