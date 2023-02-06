To compile a file called myCode.ts:

$(npm bin)/tsc --noImplicitReturns --noFallthroughCasesInSwitch --strict --noUnusedLocals myCode.ts

then run the resulting js file with node myCode.js