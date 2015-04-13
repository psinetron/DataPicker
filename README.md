# DataPicker

##How to use:

        DataPicker dpMonth = (DataPicker) findViewById(R.id.dpMonth);
        
        String[] months=new String[12];
        months[0]="january";
        months[1]="february";
        months[2]="march";
        months[3]="april";
        months[4]="may";
        months[5]="june";
        months[6]="july";
        months[7]="august";
        months[8]="september";
        months[9]="october";
        months[10]="november";
        months[11]="december";
        dpMonth.setValues(months);


##To set Value:
        dpMonth.changetToValue(SelectedMonth-1);
        
##To get current Value id:
        dpMonth.getValueid();
        
##To get current Value id:
        dpMonth.getValue();
