# Change Log

## 0.3.2

### Add

-   Supports for custom OpenAI API key and models

### Fix

-   Fixed a regression issue where commands will disappear during search

## 0.3.1

### Add

-   Commands for commonly used actions (such as "Accept Changes"), which allow users to bind keyboard shortcuts

### Fix

-   Fixed the issue where text wrapped in the placeholder pattern would be lost when inserting code snippet
-   Show alert when chatting without an active text editor

## 0.3.0

### New Features

-   Chat is now available in the CodeCursor
-   Add `Generate Code` command to the editor context menu

### Fix

-   Fixed issue where failed requests were incorrectly identified as completed

## 0.2.2

### Fix

-   Unify the display name
-   Frequent failures may occur when dealing with long code
-   Throttle the diff operation for performance

## 0.2.1

### Add

-   Automatically merge the generated contents to the current document

## 0.2.0

### Fix

-   Code generation may be interrupted unexpectedly sometimes
-   Applying changes will fail when user switched text editors after the generation task is started

### Internal

-   Core module refactor

## 0.1.2

-   Initial release
