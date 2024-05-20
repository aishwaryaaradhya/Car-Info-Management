# Car-Info-Management

--HomePage.Mater
<%@ Master Language="C#" AutoEventWireup="true" CodeBehind="HomePage.master.cs" Inherits="Car_Info_Management.HomePage" %>

<!DOCTYPE html>
<html lang="en">
<head runat="server">
    <meta charset="utf-8" />
    <title>
        <asp:ContentPlaceHolder ID="head" runat="server"></asp:ContentPlaceHolder>Car Information Management System</title>
</head>
<body>
    <form id="form1" runat="server">
        <div>
            <header>
                <h1>Car Information Management System</h1>
                <nav>
                    <ul>
                        <li><a href="Default.aspx">Home</a></li>
                        <li><a href="Login.aspx">Admin Login</a></li>
                        <li><a href="Customer.aspx">Customer</a></li>
                    </ul>
                </nav>
            </header>
            <hr />
            <asp:ContentPlaceHolder ID="ContentPlaceHolder1" runat="server">Welcome!</asp:ContentPlaceHolder>
            <hr />
            <footer>
                <p>&copy; <%: DateTime.Now.Year %> - Car Information Management System</p>
            </footer>
        </div>
    </form>
</body>
</html>


