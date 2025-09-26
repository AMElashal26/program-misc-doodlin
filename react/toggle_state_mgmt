// React 16.x code​​​​​​‌‌‌​​‌​​​‌‌​​‌‌‌​‌‌​​​‌​‌ below
import React, { useState } from "react";
import { createGlobalStyle } from "styled-components";

// Challenge Component
export function Magician() {
    const [showRabbit, setShowRabbit] = useState(false);

    const handleClick = () => {
        setShowRabbit(!showRabbit)
    }

    return (
        <div>
            <h3>Magician's Trick 🎩</h3>
            <button onClick={handleClick}>🎩 Abracadabra!</button>
            {/* Only display the paragraph below if the button is clicked first, make it disappear upon the next button click */}
            {showRabbit && <p>🐰 A wild rabbit appears!</p>}
        </div>
    );
}

function App() {
    return (
        <div className="App">
            <Magician />
        </div>
    );
}
