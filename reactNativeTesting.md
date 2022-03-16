# React Native Testing

## Utility
- Can fix bug by making test for it
- Tests can serve as documentation

## Static Analysis Tools
- Catches errors as you write
- Type checking

## Writing Testable Code
- Small modules
- Could move all lgic out of components, components could just be for rendering

## Writing Tests
- Short and only test one thing
- AAA (Arange, Act, Assert)

## Types of Tests

### Unit Tests
- Smallest pars of code (functions or classes)
- Use Mocking

### Integration Tests
- Real individual units are combined to make sure they work together

### Component Tests
- Test that components interact with the user and render properly
- Uses fireEvent class to mock user input
- Can use snapshot testing to make sure component matches, can be complicaed if snapshots too large

### End-to-End Tests
- Varifies that code works on some device (IOS, Android)
- More time consuming to write and slower to run
- More flaky (less reliable tests results)
- Due to investement should only be made for major parts of app