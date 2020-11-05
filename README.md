# validation-by-c-
You are working on a project for designing generic motherboard that accepts external components which are Bluetooth, WiFi, USB and Camera. It is designed that the selection of these modules is independent of the order of components insertion. You are responsible for the verification of the motherboard after inserting these modules with all possible orders. Design how you would test this feature, then develop a program implemented in C++ to automate the generation of all possible combination. The program should be generic to run with any number of components. Program input: - Number of Components - Components Program output using above components - comp_order.csv file in the following format: TestCaseID, Component1, Component2, Component3, Component4