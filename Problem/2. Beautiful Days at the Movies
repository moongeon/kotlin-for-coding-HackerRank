import kotlin.collections.*
import kotlin.io.*
import kotlin.math.abs
import kotlin.text.*


fun beautifulDays(i: Int, j: Int, k: Int): Int {
    var dayList = (i..j).map {
        it
    }.toMutableList()
    var result = 0
    for (i in dayList) {
        var a = i.toString().reversed().toInt()
        if (abs(i - a) % k == 0) result += 1

    }
    return result
}

fun main(args: Array<String>) {
    val first_multiple_input = readLine()!!.trimEnd().split(" ")

    val i = first_multiple_input[0].toInt()

    val j = first_multiple_input[1].toInt()

    val k = first_multiple_input[2].toInt()

    val result = beautifulDays(i, j, k)

    println(result)
}
