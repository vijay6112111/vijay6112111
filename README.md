  int i,j;
    char s[5480];
   // printf("Enter the digit frequency");
    scanf("%s",s);
    for(i=48;i<58;i++)
    {
        int a=0;
        {
            for(j=0;j<strlen(s);j++)
        
      if(s[j]==i)
      {
          a++;
      }
    }
      printf("%d ",a);
}
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}

