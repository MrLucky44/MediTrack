# Corrective Actions Log

## Key Issues and Fixes

1. **Issue**: Backend endpoint `/api/medications/` failed with 500 error  
   **Action**: Missing serializer field fixed  
   **Resolved By**: Muhammed Emir  
   **Date**: Apr 11

2. **Issue**: Firebase messages not showing on emulator  
   **Action**: Switched to real device for testing  
   **Resolved By**: Emre  
   **Date**: Apr 19

3. **Issue**: Authentication tokens not refreshing  
   **Action**: Replaced token logic with JWT refresh setup  
   **Resolved By**: Muhammed Emir  
   **Date**: Apr 14

4. **Issue**: CORS policy blocked frontend  
   **Action**: Configured `django-cors-headers` properly  
   **Resolved By**: Muhammed Emir  
   **Date**: Apr 13
