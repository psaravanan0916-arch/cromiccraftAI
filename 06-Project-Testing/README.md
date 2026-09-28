# Phase 6 – Project Testing

## Testing Objective
To verify that ComicCraft correctly accepts user input, generates comic content, creates illustrations, displays the result, and exports the comic as a PDF.

## Test Cases

### Test Case 1 – Homepage
**Expected:** Homepage loads successfully with the comic input form.

### Test Case 2 – Story Prompt
**Expected:** Story prompt is accepted.

### Test Case 3 – Character Name
**Expected:** Character information is accepted.

### Test Case 4 – Story Settings
**Expected:** Setting, tone, and art style are accepted.

### Test Case 5 – Comic Generation
**Expected:** System generates the structured comic.

### Test Case 6 – Image Generation
**Expected:** Comic panel illustrations are generated.

### Test Case 7 – Comic Preview
**Expected:** Generated panels are displayed sequentially.

### Test Case 8 – PDF Export
**Expected:** Comic is compiled into a PDF.

### Test Case 9 – API Testing
**Expected:** API endpoints respond correctly.

## API Endpoints Tested
- `/`
- `/generate`
- `/generate-comic/json`
- `/test-image`
- `/export-success`

## Testing Workflow
Input → Story Generation → Image Generation → Comic Preview → PDF Export
