# add-function-reset-draft-3
function resetMyGarage() external override {
        delete garages[msg.sender];
    }
