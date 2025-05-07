# React CorpComment App

**Demo:** https://jessumguy.github.io/react-corpcomment-app/

https://github.com/user-attachments/assets/01283ba9-a94a-4aab-805a-263344832852

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
