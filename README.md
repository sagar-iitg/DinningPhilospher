# DinningPhilospher

# Pseudo Code 1
while(true) {
    
    // Initially, thinking about life, universe, and everything
    
    think();
    
    // Take a break from thinking, hungry now
    
    pick_up_left_fork();
    pick_up_right_fork();
    
    eat();
    
    put_down_right_fork();
    put_down_left_fork();

    // Not hungry anymore. Back to thinking!
}

# Pseudo Code 2

do{
    
    wait(fork[i])
    wait(fork[(i+1)%5])

    //eat
    
    signal(fork[i])
    signal(fork[(i+1)%5])

    //think
}while(1)