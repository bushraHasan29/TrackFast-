🎯 TrackFast: Digital Analytics Demo Store
​A single-file, zero-dependency, self-contained e-commerce demo application designed to visually demonstrate Digital Analytics Tracking. This app fires simulated data layer events (like add_to_cart and purchase) and visualizes the resulting JSON payload in real-time.
​It's built entirely in a single index.html file using React and Tailwind CSS, making it easy to download, inspect, and run anywhere.
​✨ Features
​Live Event Toast: A floating notification (Toast) appears for every major user interaction (e.g., page view, click, checkout step).
​Payload Visualization: The Toast displays the exact JSON payload, including parameters like value, currency, and items, that would be sent to an actual data layer.
​GA4 & Meta Pixel Mapping: Shows the standard event name mapping for both Google Analytics 4 (purchase) and Meta Pixel (Purchase).
​Business Context: Each event explains its "Business Value" and the "Risk if Missing" (why that tracking point is crucial).
​Full E-commerce Flow: Includes home page, product detail page, cart, multi-step checkout simulation, and purchase confirmation.
​🚀 How to Run Locally (GitHub Ready)
​This is a zero-setup project.
​Clone or Download: Get the index.html file.
​Open: Double-click the index.html file in your file explorer.
​The file will open immediately in your default web browser (Chrome, Edge, Firefox, Safari) and is instantly runnable. No server, Node.js, or complex tools are required.
​💡 Concept: Why TrackFast?
​In web development, the "data layer" (where tracking events are pushed) is often invisible to the user. This application makes that process transparent.
​By interacting with the app:
​You click "Add to Cart."
​The application calls the internal track('add_to_cart', {...}) function.
​The Event Toast instantly pops up, showing you precisely what data was collected ({ item_id: 'P1001', quantity: 1, ... }).
​You can also check the browser's developer console (F12) to see the structured log of every event fired.
​This is an ideal tool for learning or teaching marketing technology, web analytics implementation, and the importance of e-commerce tracking plans.
