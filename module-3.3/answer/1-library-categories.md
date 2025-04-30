# Answer: Substrate Library Categories

## 1. Match each library prefix with its correct category:
   - `frame_*`: Runtime modules (FRAME framework)
   - `sp_*`: Substrate primitives
   - `sc_*`: Substrate client/node services
   - `pallet_*`: Specific runtime modules

## 2. Library category identification:
   - `frame_system`: Runtime modules (FRAME framework)
   - `sp_runtime`: Substrate primitives
   - `sc_service`: Substrate client/node services
   - `pallet_balances`: Specific runtime module

## 3. Importance of understanding library categories:
Understanding these categories is crucial because:
- They determine where code executes (runtime vs node)
- They affect compilation targets (native vs Wasm)
- They impact your project's architecture
- They help you organize dependencies correctly
- They indicate which features are available in different contexts
- They guide how you should approach upgrades and maintenance

## 4. Naming convention for digital assets module:
For a custom runtime module for managing digital assets, you would use the `pallet_` prefix, e.g., `pallet_assets` or `pallet_digital_assets`. This follows the Substrate convention for specific runtime modules. 