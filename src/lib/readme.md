Sorta like utils, except:
- Logic that’s stateful, config-driven, or tied to external systems
- Integrations / configurations with external sdk's / services
- Things with side effects or that initialize/configure functionality
- Example: `lib/auth.ts` might use `jwt-decode`, access cookies, and manage login state — that’s more than just a utility.
- Stuff like i18n, auth, and date/time could be util, except these often involve setup / state / initialization