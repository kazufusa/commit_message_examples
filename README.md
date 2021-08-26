# commit message examples

This is a shakyo text of https://gist.github.com/mono0926/e6ffd032c384ee4c1cef5a2aa4f778d7 .

## Add xxx

- Add -enable-experimental-nested-generics-types frontend flag
- Add --main-process flag to run specs in the main process
- Add Throws flag and ThrowsLoc to AbstracfFunctionDecl
- Add "event" handler for "click" handler of MenuItem
- Add File > Exit menu on Windows

## Add files

- Add npm start script
- Add build script
- Add SkUserConfig.h with blank SkDebugf macro

## Add methods or functions

- Add TypeLowering::hasFixedSize()
- Add overflow scrolling
- Add convenience API for demangling
- Add a typealias to avoid a build ordering dependency between projects
- Add a helper method mayHaveOpenedArchetypeOperands to SILInstruction

## Change something

- Use args.ResourcePath instead of args.devResourcePath
- Use arrays instead of while loops
- Use auto instead of repeating explicit class names
- Use weak pointer instead of manual bookkeeping
- Change all uses of 'CInt' to 'Int32' in the SDK overlay
- Change integer#year to return a Fixnum instead of a Float to improve consistency

## Add supports

- Add support for closure contexts to readMetadataFromInstance()
- Add support for activating and deactivating package-specific keymaps
- Add support for launching HTML files directly
- Add support for allocators that require tensors with zero
- Make it possible to cal `reflect` multiple times
- Make it possible to set a data type for variables that come out of constants
- Allow atom-pane to be shrunk independently of its contents' width
- Allow null TextEditorComponent::domNode during visibility check

## Use somethings

- Use const for util require
- Use FoldingSetNode for ProtocolType
- Use unique text editor title in window and tab titles
- Use an empty object if metadata is ~null
- Use target_link_libraries for fat executable dependencies
- Use existing flatMapToOptionalTests dataset

## Improve

- Make the clone function more generic
- Make IO faster for v8 compile cache
- Make model constructor argument to addViewProvider optional
- Make Browser::Quit more robust
- Improve incompatible native module error message
- Improve folds behavior when duplicating lines
- Improve deprecated message on webPreferences options

## Disable something

- Don't bail reading a metadata instance if swift_isaMask isn't available
- Don't exit until the parent asks for an instance
- Don't include Parent pointer in Nominal/BoundGeneric TypeRef uniquing
- Don't use Matches Extension for matching filters
- Don't use ES6 class for AutoUpdater windows class
- Avoid `distinct` if a subquery has already materialized
- Avoid infinite recursion when bad values are passed to tz aware fields

## Emit debug data

- Emit capture descriptors in their own section
- Emit field metadata for @objc classes
- Emit reflection into for protocols

## Add assertions

- Add assert for role with app name in label
- Add assertions for no available bookmark
- Add asserts for properties

## Remove

- Remove somde dead code
- Remove some unused enum declaration
- Remove unused variable
- Remove unnecessary line feeds
- Remove trailing whitespace
- Remove debug statement
- Remove redundant mapType{Into,OutOf{Context() calls

## Move

- Move function signature analysis to a Util
- Move markInvalidGenericSignature() to a method of TypeChacker
- Move diagnostic for stored properties in protocols from type checking to validation
- Move Doxygen converter into a proper MarkupASTNode visitor
- Move Module require to top

## Rename

- Rename environment -> environmentHelpers
- Rename watchProjectPath to watchProjectPaths
- Rename generic arguments
- s/grammarName/grammar
- fullVersion -> writeFullVersion

## Typo, minor bug, and warning

- Fix typos
- Fix a typo
- Fix a test
- Fix typo in DevTools Extensions tutorial
- Fix DownloadingState typo
- Fix includes order
- Fix mistake in tvOS availability
- Fix cpplint warnings
- Fix wrong markdown
- Add missing return
- Add missing period in comment

## Fix

- Fix a memory leak in FSO
- Fix lifetime issues in ManagedBUffer.value
- Fix mangling for nested genneric types
- Fix memory corruption in another circularity check
- Fix threada-unsafety in Process.Argument initialization
- Fix "Object has been destroyed" error in "page-title-updated" event
- Make Error.prepareStackTrace read-only (again)
- Make string slicing tests standalone
- Make sure showing success dialogs works correctly
- Make sure to emit closure bodies only once
- Make sure all native resources get freed on exit
- Make sure temp file will be cleaned up when base::Move fails

## Test, Comment and Document

- Add tests for pending pane items
- Add validation test for projecting existentials
- Add a basic test for opening and editor in larlgeFileMode if >= 2MB
- Add spacs for moveSelectionLeft()
- Add failing spec for Menu.buildFormTemplate
- Add comment about map key/values
- Add TODO about blinkFeatures -> enableBlinkFeatures
- Add a design-decisions section to the CONTRIBUTING guide
- Add style.less examples
- Add docs for app.getLocale()
- Add documentation for --proxy-bypass-list

## Remove test

- Remove a redundant test
- Remove an empty test

## Fix test and comment

- Fix comment
- Fix outdated comment
- Fix failing specs on Windows
- Fix PersistentVactor test for powerpc64{le}
- Update specs for deferred activation hooks
- Update successor/predecessor in validation tests
- Update some tests to use LifetimeTracked instead of hand-rolled canaries

## Update document

- Update README.md
- Update docs for marker callback
- Update documentation for mark*Position
- Update link to solarized-dark-syntax
- Improve documentation of `ses.cookies.set()`
- Improve readability in CSRF section of guide
- Improve spec description


