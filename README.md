# Infinite Render Loop in React useEffect Hook

This repository demonstrates a common React bug: an infinite render loop caused by a missing dependency in the `useEffect` hook. The `MyComponent` repeatedly renders because the effect function runs after every render, causing a continuous update cycle. The solution involves adding the count variable as a dependency to `useEffect`.