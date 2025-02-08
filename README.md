# Expo AsyncStorage Large Data Error

This repository demonstrates a bug encountered when using AsyncStorage in Expo applications with data exceeding the library's storage limits.  The issue manifests as a cryptic error message, making diagnosis and resolution difficult.

## Bug Description

Attempting to store a large amount of data in AsyncStorage results in an error that does not clearly indicate the size restriction as its cause.  This makes debugging and finding a solution challenging for developers.

## Solution

The solution involves using alternative storage methods better suited for managing large amounts of data, such as SQLite, MMKV, or cloud-based solutions like Firebase or Supabase.