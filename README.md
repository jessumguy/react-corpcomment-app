# React Corp

### Built using:

- React w/ Typescript, Context API and Zustand
- Radix UI

### Notes:

1. useMemo for performance optimization

- `useMemo(() => {}, [])` in `src/components/App.tsx`

2. Ways around Prop Drilling

- {children}
- Context API `src/contexts/FeedbackItemsContextProvider.tsx` and `src/componenets/lib/hooks.tsx`
- Zustand `src/stores/feedbackItemsStore.ts`

### Source:

ByteGrad Professional React and NextJS Course
