class TodoAdapter (val context : Context, val todos: ArrayList<Todo>) : RecyclerView.Adapter<TodoAdapter.ViewHolder>() {

    override fun onBindViewHolder(p0: ViewHolder, p1: Int) {
        // Binding data
      p0.txtName?.text = todos[p1].name;
    }

    override fun onCreateViewHolder(p0: ViewGroup, p1: Int): ViewHolder {
        // get view
        val v = LayoutInflater.from(p0?.context).inflate(R.layout.recycle_view_item, p0, false)
        return ViewHolder(v);
    }

    override fun getItemCount(): Int {
        // return size
        return todos.size
    }

    class ViewHolder(itemView: View) : RecyclerView.ViewHolder(itemView) {
        // hook
        val txtName = itemView.findViewById<TextView>(R.id.txtName)
    }
}
