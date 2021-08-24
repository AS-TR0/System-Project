# System-Project
Creating new things
}function exec() {
    //Open a dialog window showing the text.
    //In this case we want to show the table Accounts as html file
    Banana.Ui.showText(accounting.document.table('Accounts').toHtml(['Account', 'Group', 'Description', 'Balance'], true));

}
