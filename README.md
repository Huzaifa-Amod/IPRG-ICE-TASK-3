# IPRG-ICE-TASK-3

// Start of the program
Begin

    // Display the heading
    Display "Sammy's Seashore Supplies"

    // Prompt the user for the number of minutes rented
    Display "Enter the number of minutes rented:"
    Input minutesRented

    // Calculate the number of hours and additional minutes
    hoursRented = minutesRented // 60
    additionalMinutes = minutesRented % 60

    // Calculate the total rental cost
    totalCost = (hoursRented * 400) + (additionalMinutes * 1)

    // Display the hours, minutes, and total price
    Display "Hours rented: " + hoursRented
    Display "Additional minutes rented: " + additionalMinutes
    Display "Total cost: R" + totalCost

// End of the program
End

# FLOW CHART

[Flowchart.drawio.pdf](https://github.com/Huzaifa-Amod/IPRG-ICE-TASK-3/files/15355505/Flowchart.drawio.pdf)
