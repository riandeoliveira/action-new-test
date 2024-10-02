#!/bin/bash

echo "Select the version bump type:"
echo "1) Major"
echo "2) Minor"
echo "3) Patch"
read -p "Enter choice [1-3]: " choice

case $choice in
    1) 
        npm version major -m "Bump version to %s"
        ;;
    2) 
        npm version minor -m "Bump version to %s"
        ;;
    3) 
        npm version patch -m "Bump version to %s"
        ;;
    *) 
        echo "Invalid choice. Aborting."
        exit 1
        ;;
esac

echo "Version bumped successfully."
