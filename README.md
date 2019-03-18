# hello-world
the 1st born repository

# I need to change this page due to ....

myWebServiceTest.WebService1SoapClient myWebService = null;
         private void Form1_Load(object sender, EventArgs e)
         {
             myWebService = new myWebServiceTest.WebService1SoapClient("WebService1Soap");  
         }
         private void button1_Click(object sender, EventArgs e)
         {
             textBox1.Text = myWebService.HelloWorld();
         }

         private void button2_Click(object sender, EventArgs e)
         {
              textBox2.Text = myWebService.GetStr(textBox3.Text);
         }
