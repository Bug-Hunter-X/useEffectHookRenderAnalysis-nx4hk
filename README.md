# React useEffect Hook Runs on Every Render

This repository demonstrates a common issue with the React `useEffect` hook where it unexpectedly runs on every render instead of just once.  The problem is caused by an improperly configured dependency array.  The solution shows how to correctly specify dependencies to control execution timing.