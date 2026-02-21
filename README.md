Deploy Stack: docker stack deploy -c compose.yaml card
Scale first Stack to 7: docker service scale card_mywebsite=7
Remove Stack and delete Containers: docker stack rm card
